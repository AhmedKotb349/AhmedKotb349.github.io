# AhmedKotb349.github.io

Source for my personal portfolio site — live at **[ahmedkotb349.github.io](https://ahmedkotb349.github.io)**, also mirrored on Vercel. This repo also hosts my CV/resume files and certificates, served directly as static assets.

## 🔗 Live Pages

| Page | URL | Purpose |
|---|---|---|
| Full Portfolio | [`/index.html`](https://ahmedkotb349.github.io/index.html) | Main site — about, skills, certifications, projects, freelance CTA, contact |
| CV Page | [`/cv.html`](https://ahmedkotb349.github.io/cv.html) | Formatted on-page resume view |
| Brief Version | [`/brief.html`](https://ahmedkotb349.github.io/brief.html) | Condensed one-screen landing page |
| Freelance Services | [`/freelance.html`](https://ahmedkotb349.github.io/freelance.html) | Security assessment & landing-page build service listings |

All four pages share one design system (dark/light theme, toggled via the Control Panel burger menu in the nav) and cross-link to each other.

## 📄 Documents

| File | Description |
|---|---|
| `Ahmed_Kotb_CV.pdf` | One-page CV with clickable links — for on-screen viewing |
| `Ahmed_Kotb_CV_Print.pdf` | One-page CV with no hyperlinks, GitHub/LinkedIn as full plain-text URLs — for hard-copy printing |
| `Ahmed_Kotb_Full_Resume.docx` | Comprehensive multi-page resume covering every project, certification, and training |
| `Ahmed_Kotb_ATS_CV.txt` | Plain-text, ATS-parser-friendly version |
| `ICTHUB.pdf` | AI & Prompt Engineering Scholarship certificate — ICTHub Egypt |
| `Learn the Latest Tech Skills; Advance Your Career - Udacity.pdf` | AWS AI Practitioner certificate — Udacity |

The site links to these directly (e.g. `ahmedkotb349.github.io/Ahmed_Kotb_CV.pdf`) since GitHub Pages serves them with the correct content type for in-browser viewing — unlike `raw.githubusercontent.com`, which forces a download.

## 🎨 Design System

- **Fonts:** Syne (headings) · Space Mono (labels, code, monospace accents)
- **Palette:** teal · sky blue · copper · rose · coral red · gold — deliberately avoids purple/indigo
- **Dark/Light mode:** toggled via the Control Panel (burger icon, left of the logo in the nav bar), persisted in `localStorage`
- **Control Panel:** also provides quick navigation, a reading-progress bar, Fullscreen, and Export/Print (uses the browser's native print-to-PDF, respecting whichever theme is active)

## 🚀 Deployment

- **GitHub Pages:** builds automatically from this repo's default branch
- **Vercel:** mirrors the same repo for a secondary deployment

No build step — everything is static HTML/CSS/JS, so pushing to `main` is enough to update the live site on both platforms.

## ✏️ Updating

To update content (projects, certifications, links): edit the relevant section directly in `index.html` (source of truth for most content), then mirror any CV-related or contact-related changes into `cv.html`, `brief.html`, and `freelance.html` to keep all four pages consistent.

---

📬 **Contact:** [akotb4749@gmail.com](mailto:akotb4749@gmail.com) · [LinkedIn](https://www.linkedin.com/in/ahmed-kotb-ak349/) · [GitHub](https://github.com/AhmedKotb349)
