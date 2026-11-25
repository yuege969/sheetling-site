# sheetling-site

Sheetling 的产品页 + 法务页（Terms / Refund / Privacy）。

- 唯一真源在私有仓库 `sheetling` 的 `store/site/` 与 `store/privacy.html`；
- 本目录的 `index.html` / `terms.html` / `refund.html` / `privacy.html` / `CNAME` 都由
  `npm run site:publish` 生成，**请勿直接编辑**；
- 结账链接与价格来自 `extension-src/config.js`（那里才是单一真源）；
- GitHub Pages：Settings → Pages → Deploy from branch `main` / root；自定义域名会写到 `CNAME`。
