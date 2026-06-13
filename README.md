# Sabah Home Care — Website

A polished, single-page marketing website for **Sabah Home Care, LLC**, a Virginia‑licensed,
locally owned in‑home care agency based in Chantilly, serving families across Northern Virginia.

🔗 **Live site:** https://navidysz.github.io/sabah-homecare/

![Sabah Home Care](https://img.shields.io/badge/status-live-2f8190) ![No build step](https://img.shields.io/badge/build-none-c98a3f)

---

## ✨ Highlights

- **One self‑contained file** — everything lives in [`index.html`](index.html). No build step, no dependencies to install.
- **"Dawn" design concept** — *Sabah* means *"morning"* in Arabic/Turkish, so the design leans into a warm
  sunrise‑over‑teal palette with the elegant **Fraunces + Inter** type pairing.
- **Fully responsive** — desktop, tablet and mobile, with a collapsing hamburger menu.
- **Accessible** — semantic landmarks, skip link, focus styles, ARIA labels, and `prefers-reduced-motion` support.
- **Fast & reliable** — no external images (custom SVG art only), so it always renders, even offline.
- **Working contact forms** — the hero and contact forms open the visitor's email app with the details
  pre‑filled and addressed to the agency (no backend required).

## 🧱 Sections

Top bar · Header/nav · Hero (with consultation form) · Trust stats · About · Services ·
Why Us · How It Works · Testimonials · Service Area (Northern Virginia map) · Call‑to‑action · Contact · Footer

## 📇 Business details used

| | |
|---|---|
| **Name** | Sabah Home Care, LLC |
| **Phone** | (571) 315‑8263 |
| **Email** | sabahhomecare@yahoo.com |
| **Address** | 4221 Walney Road, Suite 500‑C, Chantilly, VA 20151 |
| **President** | Zohra Hassanzadeh |
| **NPI** | 1023635695 |
| **Licensing** | Virginia Department of Health, Office of Licensure & Certification (OLC) |
| **Service area** | Fairfax, Loudoun, Prince William & Arlington counties (Northern Virginia) |

## ✏️ Editing the content

Open [`index.html`](index.html) in any editor — it's plain HTML/CSS/JS, no framework.

- **Phone / email / address** appear in a few places (header, hero, Why‑Us panel, contact section, footer).
  Search & replace to update everywhere. The phone link format is `tel:+15713158263`.
- **Colors** are CSS custom properties in the `:root { … }` block near the top.
- **Forms** submit to `sabahhomecare@yahoo.com` via `mailto:` (see the `js-care-form` script at the bottom).
  To use a hosted form service (e.g. Formspree) instead, swap the form `action`/handler.

### 🔧 Placeholders to review before going public

- **Testimonials** are sample copy — replace with real, written client reviews (see the
  `<!-- NOTE … -->` comment above the Reviews section).
- **Office hours** (“Mon–Fri, 9:00am–5:00pm”) are an assumption — confirm and adjust in the Contact
  section and footer.

## 💻 Run locally

It's a static file — just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 4321
# then visit http://localhost:4321
```

## 🚀 Deploy (GitHub Pages)

This repo is set up to publish from the `main` branch root via GitHub Pages.
Push to `main` and the site updates automatically at the live URL above.
(Settings → Pages → Source: *Deploy from a branch* → `main` / `/root`.)

---

© Sabah Home Care, LLC. Licensed by the Virginia Department of Health (OLC).
