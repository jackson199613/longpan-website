# 龙盘 LP SeaSpark 官网首页（第四版：重工业风）

外贸英文首页展示稿。对标 Cummins、Caterpillar 官网的重工业视觉：深色钢板与水泥灰交替的大色块、窄体粗黑大写标题、切角按钮和图片、警示斜纹、等宽字体的参数标注。纯静态页面，推送到 GitHub 后由 Netlify 自动部署。

配色取自客户原有两个网站：

- SeaSpark 蓝 `#00119F`（lpseaspark.com）：品牌色，顶栏、负荷测试面板、联系区
- 富电康橙红 `#ED461C`（fudiankang.com）：强调色，按钮、编号、警示条
- 富电康钢蓝 `#1F394C` 系：深色区块底色

文件：

- `index.html`：首页
- `images/`：首页用图。机组、车间、工序、Logo 来自客户官网 lpseaspark.com；油田、海上平台、港口、电站、数据中心为 Unsplash 免费授权图片（Unsplash License，可商用）
- `preview/`：首页长图（电脑端、手机端），用于给客户看效果
- `netlify.toml`：Netlify 配置，无需构建，发布目录为仓库根目录
- `robots.txt`：允许搜索引擎和海外 AI 爬虫抓取
