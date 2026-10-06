# 曹苇航 · 个人作品集

静态网站，包含完整首页、图片、视频和 H5 小游戏。无需安装依赖。

## 在 Render 发布

在 Render 创建 **Static Site** 并连接本仓库，填写：

- Branch：`main`
- Root Directory：留空
- Build Command：`mkdir -p dist && cp index.html dist/index.html && cp -R public dist/public`
- Publish Directory：`dist`

也可以通过 Render Blueprint 导入仓库，使用根目录的 `render.yaml` 自动填写配置。

发布后由 Render 提供 HTTPS 网址。后续更新本仓库，Render 可自动重新部署。

## 本地打开

双击 `index.html` 即可，需保留旁边的 `public` 文件夹。
