# GitHub 主页维护说明

## 修改文字和链接

打开本仓库根目录 README.md，点击铅笔图标编辑，预览后点击 Commit changes，提交到默认分支即可。GitHub 账号主页 https://github.com/zjin73 会自动展示 README，无需 GitHub Pages 构建。

- 顶部：姓名、研究主题和一句话介绍。
- Research interests：研究兴趣，不代表已经取得的成果。
- Notes & projects：项目入口；新增项目按现有 Markdown 链接格式添加。
- Website & research notes：个人网站链接。

## 动态横幅

assets/network.svg 是本仓库自带的轻量网络示意图，使用 SVG 内的 CSS 动画实现缓慢流动与呼吸效果，无外部图片服务、统计卡片、脚本或自动更新任务。支持 SVG 动画的浏览器中会动态显示；其他查看器可能显示静态图。

系统开启“减少动态效果”时，动画关闭。修改 SVG 中的颜色、节点坐标和 animation 时长可调整效果；需要完全静态时，删除 .flow 和 .halo 的 animation 声明即可。图片更新可能受 GitHub 缓存影响，必要时修改图片文件名并同步 README 中的路径。

## 上传图片

图片放入 assets/，在 README 使用相对路径，例如：

```markdown
![图片说明](assets/example.png)
```

保持仓库名为 zjin73，仓库公开，根目录 README.md 非空，才能继续在账号主页展示。本仓库与个人网站 zjin73.github.io 分开维护。
