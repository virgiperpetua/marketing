# Virginia Perpetua Marketing

Static marketing / portfolio site for Virginia Perpetua — pages from the Claude Design export.

- [`assets`](https://gitlab.com/virginia-perpetua/design-system/assets) — logos, photos, banners, screenshots
- [`tokens`](https://gitlab.com/virginia-perpetua/design-system/tokens) — `--vp-*` design tokens

## Pages

| Page | Path |
| --- | --- |
| Home | [`public/index.html`](./public/index.html) |
| About | [`public/about.html`](./public/about.html) |
| Projects | [`public/projects.html`](./public/projects.html) |
| Resume | [`public/resume.html`](./public/resume.html) |
| Contact | [`public/contact.html`](./public/contact.html) |
| Design export gallery | [`public/design.html`](./public/design.html) |

Design Markdown specs: [`docs/design-export/`](./docs/design-export/).

## Local preview

```sh
python3 -m http.server 8080 --directory public
```
