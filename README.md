# STUPID QUESTIONS

## Adding a question

Drop a new file in `_faqs/`. The filename becomes the URL (`_faqs/when-is-emporium.md` → `/faq/when-is-emporium/`).

```yaml
---
title: "When is blue essence emporium?"
summary: "Short version — this is what Discord shows in the embed."
category: "Shops & Currency"
order: 3
---
The answer. Markdown or raw HTML, both work.
```

- **`category`** must match one of the names in `faq_categories` in `_config.yml`, exactly. Anything that doesn't match shows up under "Uncategorized" at the bottom of the index rather than disappearing.
- **`order`** sorts the question inside its category (low to high).
- **`summary`** is the Discord embed description, and together with the title it is what the search box on the index matches against — so keep it descriptive.

## Adding a category

Add the name to `faq_categories` in `_config.yml`. The list controls the display order on the index page; categories with no questions are skipped automatically.

## How the index works

`index.html` groups questions into a two-level accordion: category → question → answer. Each question keeps a stable anchor (`#faq-<filename>`) and its own standalone page, so links already shared on Discord keep working. Opening a question updates the URL hash, and loading a hash auto-opens the right category and question.
