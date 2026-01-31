# Blog

Blog posts live under `content/posts/` and render with the post list and single templates.

## Add a post

```toml
---
title = "Lorem Ipsum"
date = 2026-01-30T12:00:00Z
image = "/images/post-1.svg"
---
```

Write your post content below the front matter in Markdown.

## Listing

- The home page shows the latest posts automatically.
- `/posts/` lists all posts with optional thumbnails.

## Drafts

Add `draft = true` to keep a post hidden unless you run Hugo with `-D`.
