# GitHub Pages 发布

项目已包含 `.github/workflows/pages.yml`，提交到 main 后运行测试并发布 dist 静态目录。

创建 GitHub 仓库并上传项目源码（包含隐藏目录 `.github`，不上传 `.git` 和 `.openai`）。在仓库 Settings → Pages 中将 Source 设为 GitHub Actions。随后推送 main 或在 Actions 中手动运行 Deploy BookMap to GitHub Pages。

等工作流成功后，访问 Settings → Pages 显示的网址。项目的 CSS 和脚本使用相对路径，可用于仓库子路径站点。浏览器数据以站点来源为单位，本地记录不会自动迁移到 GitHub Pages，需在个人中心导出后导入。

该部署发布静态演示，不提供真实柜体、账号、支付和多人聊天服务。仓库可见性和 Pages 可用性取决于你的 GitHub 账号方案；发布前确认希望的源码和网站受众。
