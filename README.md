# kavyakadi3.github.io

Personal site of **Kavya Kadi** — software engineer in Toronto working on applied AI and backend systems.

Live at **[kavyakadi3.github.io](https://kavyakadi3.github.io/)**.

## How it's built

Deliberately boring, in the best way:

- One hand-written HTML page, one hand-written stylesheet — no framework, no build step, no dependencies.
- A few dozen lines of vanilla JS (hero word rotation, scroll reveals, mobile menu), all progressive enhancement — the site works fully with JavaScript disabled.
- Fluid type and spacing via `clamp()`, automatic dark mode via `prefers-color-scheme`, reduced motion respected via `prefers-reduced-motion`.
- Semantic landmarks, skip link, and visible focus states throughout.
- SEO: canonical URL, Open Graph/Twitter cards, JSON-LD `Person` schema, `sitemap.xml`.

## Structure

```
index.html              the whole site
assets/css/style.css    the whole design
assets/img/             headshot, project images, favicons
assets/resume/          résumé PDF
```

Hosted on GitHub Pages. To publish a change: edit, commit, push.
