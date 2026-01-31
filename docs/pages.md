# Pages

This theme supports standard Hugo pages using the default single template. The layout includes a main content column and a sticky profile card on the right.

## Available pages (exampleSite)

- Home: `/` from `content/_index.md`
- About: `/about/` from `content/about.md`
- Projects: `/projects/` from `content/projects.md`
- Services: `/services/` from `content/services.md`
- Contact: `/contact/` from `content/contact.md`

## Page front matter

You can add an optional image to any page:

```toml
---
title = "Lorem Ipsum"
image = "/images/page-about.svg"
---
```

If `image` is set, it appears below the title as a wide hero image.

## Content

The main content supports headings, lists, and images. Keep text in plain Markdown under each page in `content/`.
