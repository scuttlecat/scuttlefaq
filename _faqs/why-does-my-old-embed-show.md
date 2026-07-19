---
title: "I edited an answer but Discord shows the old embed. Why?"
summary: "Discord caches embeds per URL. Wait for the cache to expire, or force a fresh embed by appending a query string like ?v=2 to the link."
order: 3
---
Discord caches link embeds server-side, per URL. If you change an
answer's `summary`, links that were *already posted* keep their old
embed, and even newly posted links may show the cached version for a
while.

To force a fresh embed immediately, post the link with a throwaway
query string, e.g.:

```
https://you.github.io/repo/faq/my-question/?v=2
```

Discord treats that as a new URL and fetches your page again.
