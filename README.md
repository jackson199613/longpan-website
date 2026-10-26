# 龙盘 LP SeaSpark 官网首页（第一版）

外贸英文首页展示稿，纯静态页面，推送到 GitHub 后由 Netlify 自动部署。

- `index.html`：首页（样式和脚本都在这一个文件里）
- `netlify.toml`：Netlify 配置，无需构建，发布目录为仓库根目录
- `robots.txt`：允许搜索引擎和海外 AI 爬虫抓取

图片目前直接引用客户现网 lpseaspark.com 的图片地址，正式上线前建议把图片放进本仓库 `images/` 文件夹。
询盘表单和技术评估表单使用 Netlify Forms，部署后在 Netlify 后台的 Forms 里查看提交。
