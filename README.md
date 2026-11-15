<p align="center">
  <a href="https://alpharev.vercel.app"><img src="og.png" alt="AlphaRev" width="100%"></a>
</p>

# AlphaRev | ألفا ريف

**Custom digital systems for organizations and individuals.**
حلول وأنظمة رقمية مخصصة للجهات والأفراد

**Live site:** [alpharev.vercel.app](https://alpharev.vercel.app)

---

## What it is

AlphaRev is the studio site for my freelance work. It presents the systems I build for organizations and individuals, the way I work, and a record of past work, in Arabic and English.

## Highlights

- **Bilingual by design:** one page, full Arabic (RTL) and English (LTR) with an instant toggle; every string lives in one translation object.
- **Single-file build:** the whole site is one `index.html` with inline CSS and JavaScript, no framework and no build step, so it loads fast and deploys anywhere.
- **Solutions catalogue:** offerings grouped by market need, each with sample workflows such as multi-step approvals.
- **Work log:** filterable record of projects, awards and certifications.
- **Digital business card:** `card.html` with a downloadable contact file (`nora.vcf`) served with the correct vCard headers.
- **Share-ready:** Open Graph preview image, favicons and app icons.
- **Accessible motion:** animations respect `prefers-reduced-motion`.

## Files

| File | Purpose |
|---|---|
| `index.html` | Main site (Arabic / English) |
| `card.html` | Digital business card |
| `nora.vcf` | Contact card download |
| `vercel.json` | Clean URLs and vCard headers |
| `og.png`, `card-preview.jpg` | Social preview images |
| `favicon.png`, `apple-touch-icon.png`, `icon-512.png` | Icons |

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

Deployed on Vercel as a static site. `vercel.json` enables clean URLs and serves `nora.vcf` as a download.

---

Designed & Developed by Nora Aldossari · [Portfolio](https://nora-aldossari.vercel.app)
