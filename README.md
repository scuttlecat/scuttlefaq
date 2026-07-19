# FAQ site with per-question Discord embeds

A tiny Jekyll site for GitHub Pages. Every question lives in `_faqs/` as
a Markdown file and gets:

- an entry (with anchor) on the main FAQ page, and
- **its own URL** at `/faq/<filename>/` with its own Open Graph tags —
  so pasting that URL into Discord shows the question + answer as an embed.

## Setup

1. Create a new GitHub repo and push these files to the default branch.
2. Edit `_config.yml`: set `url` and `baseurl` (instructions are in the file),
   plus `title` and `description`.
3. On GitHub: **Settings → Pages → Build and deployment → Source:
   "Deploy from a branch"**, pick your branch and `/ (root)`, save.
4. Wait a minute or two. Your site is at
   `https://USERNAME.github.io/REPO-NAME/`.

No local install needed — GitHub runs Jekyll for you on every push.

## Adding a question

Create `_faqs/some-slug.md`:

```yaml
---
title: "The question?"
summary: "Short plain-text answer shown in the Discord embed (~300 chars max)."
order: 4
---
Full answer in Markdown.
```

`order` controls position on the index page. The filename controls the URL.

## Notes

- The share URL for each question is shown under its answer on the index page.
- Discord caches embeds per URL; append `?v=2` (any query string) to force a refresh.
- `embed_color` in `_config.yml` sets the colored stripe on the Discord embed.

## Optional: run locally

Only needed if you want to preview before pushing:

```
gem install bundler jekyll
jekyll serve
```

Then open http://localhost:4000/YOUR-REPO-NAME/
