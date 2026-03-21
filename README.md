# GitHub Pages 手机版部署包

文件说明：
- index.html：主页
- 404.html：防止直接访问子路径时报 404
- .nojekyll：避免 GitHub Pages 处理异常

最短部署步骤：
1. 新建 GitHub 仓库
2. 上传这 3 个文件到仓库根目录
3. 进入 Settings → Pages
4. Source 选 Deploy from a branch
5. Branch 选 main / root
6. 保存后等待 1~3 分钟
7. 网址通常会是：https://<你的用户名>.github.io/<仓库名>/
