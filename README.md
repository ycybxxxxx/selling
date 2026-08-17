# 摊位小店 GitHub Pages 版本

- `index.html`：顾客页面，不显示摊主管理入口。
- `admin.html`：摊主管理后台，需要 PIN 验证。
- `.nojekyll`：直接作为静态站点发布。

部署后通常：

- 顾客端：`https://你的用户名.github.io/仓库名/`
- 后台：`https://你的用户名.github.io/仓库名/admin.html`

## 重要限制

当前商品、图片、二维码、订单和 PIN 都使用浏览器 localStorage。
不同设备之间不会同步。若要让摊主后台修改商品后所有顾客立即看到，需要接入云数据库/后端，例如 Supabase 或 Firebase。


默认管理 PIN：`30102`
