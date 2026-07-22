<div align="center">

# Cottonil — Assiut Branch · Official Storefront &nbsp;| &nbsp;قطونيل — فرع أسيوط

**A sleek, fully responsive Arabic (RTL) storefront for premium Egyptian cotton apparel** — featuring a dynamic product catalog, instant live search, category filters, a rich product-detail modal, and one‑tap ordering over WhatsApp.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Store-E9B949?style=for-the-badge&logo=githubpages&logoColor=white)](https://3mmar404.github.io/cottonil-assiut-store/)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](#-tech-stack)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](#-tech-stack)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](#-tech-stack)
[![Deployed on GitHub Pages](https://img.shields.io/badge/Deployed-GitHub_Pages-222?style=flat-square&logo=github&logoColor=white)](https://3mmar404.github.io/cottonil-assiut-store/)
[![License: MIT](https://img.shields.io/badge/License-MIT-3DA639?style=flat-square)](#-license)

</div>

---

## Overview

**Cottonil – Assiut Branch** is the official storefront for the Cottonil retail branch in Assiut, Egypt. It presents the store's premium cotton collection in an elegant, dark‑themed, right‑to‑left (RTL) interface built entirely with **vanilla HTML, CSS, and JavaScript** — no frameworks, no build step.

Visitors can browse the full catalog, search and filter products, inspect details (colors, sizes, and pricing) in a pop‑up gallery, and place an order in a single tap through WhatsApp. The site is deployed as a static site on GitHub Pages.

> **Live site:** https://3mmar404.github.io/cottonil-assiut-store/

---

## Features

- 🛍️ **Dynamic product catalog** — products are rendered from a central data file (`js/products.js`), making the store easy to update and extend.
- 🔎 **Instant live search** — filter products by name in real time as you type.
- 🏷️ **Category filters** — quick toggles for collections (All, Cottonil, Kids, Women's *vega*, and extras).
- 🖼️ **Product‑detail modal** — a pop‑up with an image slider, available colors, size range, and price.
- 💬 **One‑tap WhatsApp ordering** — every product links to a pre‑filled WhatsApp message to complete the order instantly.
- 🏅 **Product badges** — highlight items as *New*, *Basic*, or *Best‑seller*.
- 📱 **Fully responsive & mobile‑first** — adaptive layout with a dedicated mobile navigation menu.
- 🌙 **Refined dark theme** — deep charcoal palette with gold accents for a premium feel.
- ✨ **Motion & polish** — animated typewriter hero, scroll‑reveal sections, and smooth in‑page navigation.
- 🌐 **Native RTL Arabic layout** — typography and structure designed for Arabic reading direction.

---

## Screenshots

### Home / Hero
<div align="center">
  <img src="https://pub.hyperagent.com/api/published/pbf01KY5NF222_ESJ0HZZQNPC7WY8J/5ab68602-ddfe-4033-9880-4c36d0dac3f2.jpg" alt="Cottonil Assiut — animated hero section with headline and call to action" width="100%">
</div>

### Product Catalog — Search & Filters
<div align="center">
  <img src="https://pub.hyperagent.com/api/published/pbf01KY5NF7CZ_P1Z8DFJ993J2PPY5/87bb90b9-a1fe-48eb-8fb5-2a61b1ea804e.jpg" alt="Product gallery with live search bar, category filter buttons, and product cards" width="100%">
</div>

### Product Modal &nbsp;·&nbsp; Mobile View
<table>
  <tr>
    <td width="60%"><img src="https://pub.hyperagent.com/api/published/pbf01KY5NF7P9_KFWA48AGE2D9AWPF/be6d1414-a4c3-498c-b003-8c25cf8074c2.jpg" alt="Product detail modal showing image slider, colors, sizes, price, and WhatsApp order button" width="100%"></td>
    <td width="40%"><img src="https://pub.hyperagent.com/api/published/pbf01KY5NF8TK_70SV6STFKTNXCJ5K/ca9d3663-844c-4c94-ade5-b918c75036f6.jpg" alt="Responsive mobile layout with hamburger navigation" width="100%"></td>
  </tr>
</table>

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Markup | HTML5 (semantic, `dir="rtl"`) |
| Styling | CSS3 — custom properties, transitions/animations, responsive media queries (`css/styles.css`) |
| Behavior | Vanilla JavaScript (ES6) — catalog data & rendering (`js/products.js`), UI interactions (`js/main.js`) |
| Icons | [Font Awesome 6.5.1](https://fontawesome.com/) (via CDN) |
| Hosting | [GitHub Pages](https://pages.github.com/) |

No frameworks, bundlers, or dependencies to install — it runs straight from static files.

---

## Getting Started

Clone the repository and open it locally.

```bash
# 1) Clone
git clone https://github.com/3mmar404/cottonil-assiut-store.git
cd cottonil-assiut-store
```

**Option A — open directly**

Just open `index.html` in your browser.

**Option B — run a local server (recommended for correct asset paths)**

```bash
# Python 3
python3 -m http.server 8000

# …or Node
npx serve .
```

Then visit **http://localhost:8000**.

---

## Project Structure

```text
cottonil-assiut-store/
├── index.html          # Main page — semantic, RTL HTML5
├── css/
│   └── styles.css      # Theme, layout, animations, responsive rules
├── js/
│   ├── products.js     # Product catalog data + rendering logic
│   └── main.js         # UI: navigation, search, filters, modal, animations
├── img/                # Product & interface images
└── README.md
```

---

## Store Information

| | |
|---|---|
| 🏬 **Store** | Cottonil — Assiut Branch (قطونيل — فرع أسيوط) |
| 📍 **Address** | Abraj El‑Nasr, Tower 2A — opposite the Health Directorate, Al‑Azhar, Assiut |
| 🕚 **Hours** | Daily, 11:00 AM – 12:00 AM |
| 📞 **Phone** | 01270483365 · 0882071432 |
| 💬 **WhatsApp** | [wa.me/201270483365](https://wa.me/201270483365) |

---

## Contributing

Contributions, issues, and feature requests are welcome.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

Designed & developed with passion 🔥 · © 2025–2026 **Ahmed Amar** ([@3mmar404](https://github.com/3mmar404))

</div>
