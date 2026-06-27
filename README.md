# 🛒 Amazon.in Homepage Clone (HTML & CSS)

A static, front-end recreation of the **Amazon.in** homepage — built with plain **HTML and CSS** to practise real-world layout: a multi-column header, a category navigation bar, a hero banner, and a grid of promotional product cards.

---

## 📌 Problem Statement

Recreating a production homepage like Amazon's is one of the best ways to learn front-end fundamentals: it forces you to reproduce a dense, responsive-looking header (logo, address selector, search bar, language picker, account dropdown, cart), a horizontal category nav, and a card grid — using only HTML structure and CSS layout (Flexbox/Grid), no frameworks.

This project rebuilds that homepage from scratch to practise:

- **CSS Grid & Flexbox** for the header and product-card layout
- **Hover states & a dropdown menu** (the "Account & Lists" panel)
- **Embedding media** (a hero video and remote product images)
- Structuring a non-trivial page with semantic, reusable classes

---

## ✨ What it includes

- 🔝 Amazon-style top header — brand, deliver-to address, search bar with category select, language picker, account dropdown, returns, and cart
- 🧭 Secondary category navigation bar (All, Best Sellers, Mobiles, Today's Deals, …)
- 🎬 Hero video banner
- 🃏 Promotional product-card grid with hover effects

---

## 🛠️ Tech Stack

- **HTML5** — page structure
- **CSS3** — Grid, Flexbox, hover transitions
- **Font Awesome 4** — icons (loaded via CDN)

---

## 🚀 How to view it

It's a static site — no build step or server needed.

```bash
git clone https://github.com/tejasdavande/amazon_html_css.git
cd amazon_html_css
open index.html        # macOS  (use "start" on Windows, "xdg-open" on Linux)
```

Or host it for free with **GitHub Pages**: repo **Settings → Pages → Deploy from branch → main → /(root)**, then open the published URL.

---

## 🗂️ Files

```
amazon_html_css/
├── index.html         # page markup
├── style_header.css   # header + category-nav styles
└── background.css     # hero banner + product-card styles
```

---

## 📝 Notes

- This is a **front-end learning project** — visual clone only, with no shopping functionality.
- Product images, the banner video, and icons are loaded from remote URLs, so an internet connection is needed to see them.
- All trademarks and assets belong to Amazon; this exists purely for educational practice.
