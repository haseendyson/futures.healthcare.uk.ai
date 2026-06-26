# Conversational Care — Healthcare Futures Landing Page

A research project landing page for **Conversational Care**, developed at Imperial College London. The site presents a conversational AI method for more inclusive healthcare futures, aimed at funders, collaborators, and implementation partners.

## About the project

This project develops a culturally responsive micro-narrative approach that helps communities reflect on healthcare experiences, articulate future priorities, and generate richer insight for research, service design, and innovation.

**Lead researchers**
- Dr Mohammad Haseen Akhtar — m.akhtar1@imperial.ac.uk
- Professor Rafael Calvo — r.calvo@imperial.ac.uk

## About this repository

A single-file static landing page (`index.html`) with no build step, no dependencies, and no framework required. Everything — HTML, CSS, and JavaScript — lives in one file.

**Stack**
- Vanilla HTML5, CSS3, and JavaScript
- Google Fonts (Inter) loaded via CDN
- Intersection Observer API for scroll-triggered animations
- Respects `prefers-reduced-motion`

## Getting started

```bash
git clone https://github.com/haseendyson/futures.healthcare.uk.ai.git
cd futures.healthcare.uk.ai
open index.html   # or drag into any browser
```

No install step needed.

## Deploying

### GitHub Pages (recommended)

1. Go to your repo on GitHub
2. Settings → Pages
3. Source: `main` branch, `/ (root)`
4. Save — your site will be live at `https://haseendyson.github.io/futures.healthcare.uk.ai`

To use a custom domain, add a `CNAME` file containing your domain name to the root of the repo, then configure your DNS as directed by GitHub.

### Any static host

Upload `index.html` to Netlify, Vercel, Cloudflare Pages, or any web server. No configuration required.

## Customising

| What | Where in `index.html` |
|---|---|
| Contact email addresses | Search `m.akhtar1@imperial.ac.uk` and `r.calvo@imperial.ac.uk` |
| Project summary link | Replace the `mailto:` on "Request Project Summary" with a direct PDF URL |
| Navigation labels | `<nav class="desktop-nav">` and `<div class="mobile-menu">` |
| Pillar / outcome copy | `.pillar-card` and `.outcome-card` elements |
| Colour accent | CSS variable `--blue-600` in `:root` |

## Licence

Content © Imperial College London. Code released under the MIT Licence — see `LICENSE` for details.
