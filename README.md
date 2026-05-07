# n-hgc — App Legal

Privacy policies and legal documents for apps published by **n-hgc**, served via GitHub Pages.

🔗 **Live site:** https://n-hgc.github.io/legal/

## Layout

```
.
├── _config.yml             # Jekyll configuration
├── index.md                # Landing page
└── <app-name>/
    ├── privacy-policy-en.md
    ├── privacy-policy-ja.md
    ├── support-en.md       # optional, per app
    └── support-ja.md       # optional, per app
```

## Adding a New App

1. Create a new folder named after the app (e.g. `marky/`).
2. Add `privacy-policy-en.md` and `privacy-policy-ja.md` (and `support-*.md` if a public support page is needed).
3. Link them from `index.md`.
4. Commit and push — GitHub Pages will rebuild automatically.

## Apps Included

- **Ikura — Daily Budget** ([privacy en](./ikura/privacy-policy-en.md) / [privacy ja](./ikura/privacy-policy-ja.md))
- **MarkyMD — Markdown Viewer for macOS** ([privacy en](./marky/privacy-policy-en.md) / [privacy ja](./marky/privacy-policy-ja.md) / [support en](./marky/support-en.md) / [support ja](./marky/support-ja.md))

## Local Preview

```bash
bundle exec jekyll serve
```

(Optional — GitHub Pages will render automatically without local Jekyll.)
