# 筑造 GitHub Pages

这个仓库用于发布「筑造」iOS App 的公开网页，满足 App Store Connect 对 App 首页、隐私政策和支持页的要求。

## 页面

- 首页：`https://firestige.github.io/just-build/`
- 隐私政策：`https://firestige.github.io/just-build/privacy.html`
- 支持页：`https://firestige.github.io/just-build/support.html`
- English home: `https://firestige.github.io/just-build/en/`
- English privacy policy: `https://firestige.github.io/just-build/en/privacy.html`
- English support: `https://firestige.github.io/just-build/en/support.html`
- 支持邮箱：`support@firestige.xyz`

支持页中的邮件入口会预填反馈模板，并固定包含 `App: 筑造 (just-build)` 与 `Bundle ID: xyz.firestige.justbuild`，用于区分用户来自哪个 App。

## 发布方式

在 GitHub 仓库设置中启用 Pages：

1. 打开 `Settings` -> `Pages`
2. `Build and deployment` 选择 `Deploy from a branch`
3. Branch 选择 `main`，目录选择 `/ (root)`
4. 保存后等待 GitHub Pages 完成部署

站点是纯静态 HTML/CSS，不需要构建步骤。
