# eugeniorogav.com

Personal portfolio — Hugo, custom CSS, Cloudflare Pages.

## Dev

```bash
hugo server
```

## Build

```bash
hugo --minify
```

Output in `public/`.

## Deploy

Cloudflare Pages connected to GitHub repo.

- Build command: `hugo --minify`
- Build output directory: `public`
- Framework preset: Hugo

## Add a case study

Create a `.md` file in `content/work/`:

```markdown
---
title: "Project Name"
summary: "One-line description of the project."
---

Content here.
```

## Structure

```
content/
  _index.md         homepage data (all sections)
  work/             case studies
    botbarn.md
    moneyflow.md
layouts/
  _default/baseof.html
  index.html        single-page homepage
  work/single.html  case study detail
assets/
  css/main.css
static/
```
