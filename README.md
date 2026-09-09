# cv

Personal CV / portfolio site for **Miloš Ursulović** — full-stack & systems engineer.

Single static page (`index.html`), no build step, no framework — plain HTML/CSS with a small vanilla-JS sprinkle for scroll-reveal animations and a copy-to-clipboard email button.

## Sections

- **About** — background across systems administration, software development, and cloud
- **Experience** — timeline of roles (Bor Health Center, Bor General Hospital, Zanix, BeeIT, VD System, Aldutek)
- **Education**
- **Skills** — Systems & Infrastructure, Backend, Frontend, Mobile, Tools & Practice
- **Projects** — pinned GitHub repos (`minic-os`, `net-desk`, `nebula`, `vortex`, `shop-daily`, `vnc`) plus links to other repos grouped by category
- **Contact** — email, phone, GitHub, LinkedIn

## Design

Dark, monochrome, terminal/register-inspired aesthetic. `JetBrains Mono` font. No CSS framework — hand-written styles in a single `<style>` block in `index.html`.

## Run locally

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Structure

```
index.html      — the entire site (markup + styles + script)
photo.jpg        — portrait
favicon.*        — favicons (svg + png sizes)
```

## Contact

- ✉ milosursulovic2696@gmail.com
- [GitHub](https://github.com/milosursulovic)
- [LinkedIn](https://www.linkedin.com/in/milos-ursulovic-a925201b3/)
