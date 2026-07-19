---
title: "How do I add a new question?"
summary: "Create a new .md file in the _faqs folder with title, summary, and order in the front matter. GitHub Pages rebuilds the site automatically on push."
order: 2
---
Create a new file in the `_faqs/` folder, e.g. `_faqs/my-question.md`:

```yaml
---
title: "The question, as a sentence?"
summary: "The short answer Discord will show in the embed."
order: 3
---
The full answer goes here, in Markdown.
```

The filename becomes the URL: `_faqs/my-question.md` → `/faq/my-question/`.
Commit and push — GitHub Pages rebuilds within a minute or two.
