# Cekrypto Landing Page

This is the public landing page for [cekrypto.com](https://cekrypto.com), built with pure HTML/CSS and deployed via GitHub Pages.

---

## 🔍 Overview

**Cekrypto** is a curated crypto intelligence platform for traders, teams, and systems.

This landing site includes:

- 🎯 Minimal, fast-loading, brand-first communication
- 🌐 Bilingual interface (English & Bahasa Indonesia)
- 📋 Clear segmentation of use cases: Traders, Teams, and Systems
- 🧠 Problems & solutions tailored to user groups via `/problems.html`
- 🚫 SEO-stealth enabled (`robots.txt`, meta `noindex`, and `_headers`)
- 🌀 Redirects users from `cekrypto.github.io` to `cekrypto.com`
- 🛡️ Fallback UI for users with JavaScript disabled (`<noscript>`)
- 🧭 Canonical links to avoid duplicate indexing

---

## 🗂️ File Structure

| File                          | Description                                                    |
|-------------------------------|----------------------------------------------------------------|
| `index.html`                  | Homepage with logo, tagline, bilingual toggle, and CTAs        |
| `problems.html`               | Detailed overview of problems Cekrypto solves for each segment |
| `cekrypto-logo-512-proportional.png` | Branded proportional logo used on homepage                  |
| `cekrypto-favicon-32x32-black.ico`   | Favicon `.ico` for broad browser compatibility              |
| `cekrypto-favicon-32x32-black.png`         | PNG favicon for modern browsers and mobile                   |
| `_headers`                    | Custom HTTP headers (for Netlify/GitHub Pages hardening)       |
| `robots.txt`                  | Blocks crawler indexing (`Disallow: /`)                        |

---

## 🚀 Deployment

| Item               | Value                                     |
|--------------------|--------------------------------------------|
| Static Host        | GitHub Pages (`main` branch)               |
| Custom Domain      | [https://cekrypto.com](https://cekrypto.com) |
| DNS Provider       | Cloudflare                                 |
| Build System       | None (vanilla HTML/CSS/JS only)            |

---

## 📌 Notes

- This landing page is part of the MVP rollout for Cekrypto.
- All insights displayed are educational only and do not constitute financial advice.
- Future releases will integrate scroll animations, embedded onboarding flows, and insight samples.
- A fallback `<noscript>` message ensures accessibility even without JavaScript enabled.

---

## 📧 Contact

For updates, collaboration, or access requests:

- ✉️ Email: [hello@cekrypto.com](mailto:hello@cekrypto.com)
- 🌐 Website: [https://cekrypto.com](https://cekrypto.com)
