# 芹菜P的主页


**[→ 访问主页](https://www.serinap.top)**

---

## 找到我

| 平台 | 链接 |
|------|------|
| X (Twitter) | [@Serina765P](https://x.com/Serina765P) |
| YouTube | [@Serina765P](https://www.youtube.com/@Serina765P) |
| Bilibili | [space.bilibili.com/1726354044](https://space.bilibili.com/1726354044) |
| Steam | [serinap](https://steamcommunity.com/id/serinap/) |
| Blog | [blog.serinap.top](https://blog.serinap.top) |

---

## 技术结构

纯静态页面，无构建步骤，无框架依赖。

- **`index.html`** — 全部结构、样式与逻辑
- **`data/profile.json`** — 个人信息与偶像卡片数据
- **`data/i18n.json`** — 中 / 日 / 英 三语文本
- **`data/data.json`** — 社交链接与游戏 ID
- **`pages/`** — 附属页面

使用 Tailwind CSS v3（CDN）、Font Awesome 6.4、Google Fonts，支持亮色 / 暗色主题切换与三语言切换。

本地预览需要通过服务器访问（页面使用 `fetch()` 加载 JSON）：

```bash
npx serve .
# 或
python -m http.server 8080
```
