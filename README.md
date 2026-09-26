# Spark — Official Website

![Spark Website Preview](assets/preview.jpg)

Official website for **Spark**, an English-medium academic coaching centre based in Uttara, Dhaka. Founded in 2019, Spark has grown from a single student to a community of 1,500+ learners preparing for Cambridge (CIE) and Edexcel (Pearson) qualifications.

Live site: *(add your Hostinger domain here once deployed)*

---

## Pages

| File | URL | Description |
|------|-----|-------------|
| `index.html` | `/` | Main site — all sections |
| `ignite.html` | `/ignite` | Ignite Cup football tournament |
| `ember.html` | `/ember` | Ember Global study abroad initiative |

---

## Project structure

```
spark-website/
├── index.html
├── ignite.html
├── ember.html
├── .htaccess           # Clean URLs (removes /index.html and .html extensions)
├── css/
│   └── main.css
├── js/
│   └── main.js
└── assets/
    └── images/         # All photos go here (.webp format)
```

No frameworks, no build tools. Just HTML, CSS, and vanilla JavaScript.

---

## Adding images

Drop your images into `assets/images/` using these exact filenames. The site expects `.webp` format for best performance.

| File | Where it appears |
|------|-----------------|
| `logo.png` | Header (all pages) |
| `favicon.png` | Browser tab (all pages) |
| `hero.webp` | Hero background — full screen |
| `intro.webp` | Our Story section |
| `curriculum.webp` | Curriculum section |
| `student1.webp` | Life at Spark gallery |
| `student2.webp` | Life at Spark gallery |
| `student3.webp` | Life at Spark gallery |
| `team1.webp` | Faculty — Tausiful Islam |
| `team2.webp` | Faculty — Fahim Rahman |
| `team3.webp` | Faculty — Dewan Fahim Faysal |
| `team4.webp` | Faculty — Karina Karim |
| `team5.webp` | Faculty — Afra Anika Nawar Khan |
| `team7.webp` | Faculty — Nabila Islam Khan |
| `team8.webp` | Faculty — Raha Rahman |
| `team10.webp` | Faculty — Abdullah Abu Bakar |
| `team11.webp` | Faculty — Ajoy Saha |
| `facility1.webp` | Facilities — Main classroom |
| `facility2.webp` | Facilities — Prayer room |
| `facility3.webp` | Facilities — Breakout room |
| `facility4.webp` | Facilities — Parents lounge |
| `ignite1.webp` | Ignite Cup section (index) |
| `ignite2.webp` | Ignite Cup section (index) |
| `ember.webp` | Ember Global section (index) |

Images for `ignite.html` and `ember.html` are referenced inside those files directly.

---

## Running locally

1. Open the folder in VS Code
2. Install the **Live Server** extension
3. Right-click `index.html` → Open with Live Server

---

## Deployment on Hostinger

1. Upload all files to `public_html/` keeping the folder structure intact
2. The `.htaccess` file handles clean URLs automatically — `yoursite.com/ignite` instead of `yoursite.com/ignite.html`
3. Enable **Gzip/Brotli compression** in Hostinger control panel
4. Enable **LiteSpeed Cache** if available on your plan

---

## Updating content

**Registration form** — search `forms.gle` in any HTML file and replace the URL.

**Contact form** — uses Web3Forms. The access key is in `js/main.js`. Replace it at web3forms.com if needed.

**Phone numbers** — search `01747230235` across all HTML files to update.

**Social links** — search `facebook.com/share`, `instagram.com/sparkdhk`, `instagram.com/ignitedhk`, `instagram.com/emberdhk` to update.

**Canonical URLs** — update `sparkdhaka.com` in the `<link rel="canonical">` tags in all three HTML files to your actual domain.

---

## Built with

- HTML5
- CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (scroll animations, mobile nav, contact form)
- Google Fonts — DM Serif Display + Plus Jakarta Sans
- Web3Forms — contact form backend
- Google Maps Embed — location widget

---

## Copyright

&copy; 2026 Nahian & Spark Education Group. All rights reserved.

*Spark Education Group · Uttara, Dhaka, Bangladesh*
