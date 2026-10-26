# yourlore-privacy

「你探 / YourLore · Urban Legend Pilgrimage」隐私政策与用户协议静态页面。

本仓库通过 GitHub Pages 发布为公开网址，供 App Store Connect、Google Play 及中国大陆各安卓应用商店填写「隐私政策 URL」「用户协议 URL」使用。

## 文件结构

| 文件 | 用途 |
|---|---|
| `index.html` | 选版落地页（根网址直接打开，含隐私政策与用户协议各三个语言版本入口） |
| `privacy.html` | 隐私政策 · 海外版（英文）—— App Store / Google Play 填写此文件的网址 |
| `privacy-cn.html` | 隐私政策 · 大陆版（简体中文）—— 微信小程序及国内安卓商店适用 |
| `privacy-ja.html` | プライバシーポリシー · 日本語版 —— 日本リージョン（App Store JP / Google Play JP）向け |
| `terms-cn.html` | 用户协议 · 大陆版（简体中文）—— 微信小程序及国内安卓商店适用 |
| `terms.html` | 用户协议 · 海外版（英文）—— App Store / Google Play 填写此文件的网址 |
| `terms-ja.html` | 利用規約 · 日本語版 —— 日本リージョン（App Store JP / Google Play JP）向け |

## 公开网址

- 落地页：`https://liumaojierichard-design.github.io/yourlore-privacy/`
- 隐私政策 · 海外版：`https://liumaojierichard-design.github.io/yourlore-privacy/privacy.html`
- 隐私政策 · 大陆版：`https://liumaojierichard-design.github.io/yourlore-privacy/privacy-cn.html`
- プライバシーポリシー · 日本語版：`https://liumaojierichard-design.github.io/yourlore-privacy/privacy-ja.html`
- 用户协议 · 大陆版：`https://liumaojierichard-design.github.io/yourlore-privacy/terms-cn.html`
- 用户协议 · 海外版（英）：`https://liumaojierichard-design.github.io/yourlore-privacy/terms.html`
- 利用規約 · 日本語版：`https://liumaojierichard-design.github.io/yourlore-privacy/terms-ja.html`

## 已填与待填

已填实（不要改动）：运营主体、版本号 `1.0.0`、更新/生效日期 `2026-10-23`、隐私/法务邮箱 `liumaojie@fissiles.com`、办公通信地址。

> **仅剩 1 项待填：ICP 备案号**。`privacy.html`、`privacy-cn.html`、`privacy-ja.html` 中各有一至两处占位（§1.1 / §12 或 §第1条 / §第13条），等工信部备案下号后替换为正式备案号并去掉高亮样式。

## 维护约定

- 本仓库是**发布源**，改动即对外生效；改完请顺手刷新网址自查一遍。
- 微信小程序里内嵌了一份大陆版隐私政策（主仓库 `source/pages/me/privacy.vue`）与用户协议（`source/pages/me/terms.vue`），此处文字变更后需同步过去，否则小程序内展示与公开网址不一致。
- 文字权威源在主仓库 `docs_项目文档/`（`隐私政策_中国大陆版_*.md`、`隐私政策_海外版_*.md`、`隐私政策_日文版_*.md`、`用户协议_中国大陆版_*.md`、`用户协议_英文版_*.md`、`用户协议_日文版_*.md`）。
- 三语政策的事实基础必须与代码一致：零网络请求、无账号、无第三方 SDK、权限只有四个（相册写入 / 相册读取+相机 / 位置 / 剪贴板写入）。打卡距离校验只在「标记去过」时取一次位置，不后台、不存轨迹、不传输。任一语言版本改动后，其余语言版本需同步复核。
