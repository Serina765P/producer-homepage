# 芹菜P的主页

> 一个关于偶像、游戏和热爱的个人主页。

**[→ 访问主页](https://serina765p.github.io/producer-homepage/)**

---

## 关于这里

这是 **芹菜P（SerinaP / セリナＰ）** 的个人主页，一位 IDOLM@STER 系列的制作人。

页面上展示了她担当的偶像们：

| 偶像 | 系列 |
|------|------|
| 天海春香 | 765PRO ALLSTARS |
| 如月千早 | 765PRO ALLSTARS |
| 横山奈绪 | MILLION LIVE! |
| 北上丽花 | MILLION LIVE! |
| 贺阳燐羽 | Gakuen IDOLM@STER |

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
