# Theme configuration

All theme settings are controlled in `config.toml` under `[params]`.

## Core params

```toml
[params]
  subtitle = "Lorem ipsum dolor sit amet"
  tagline = "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
  hero_kicker = "Lorem ipsum"
  hero_title = "Lorem ipsum dolor sit amet"
  hero_intro = "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
  profile_image = "/images/hero-placeholder.svg"
  hero_image = "/images/hero-placeholder.svg"
  theme_name = "Mikosch"
  feature_title = "Lorem ipsum"
  feature_intro = "Lorem ipsum dolor sit amet"
  posts_title = "Lorem ipsum"
  posts_intro = "Lorem ipsum dolor sit amet"
  profile_blurb = "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
```

## Calls to action

```toml
[params.cta_primary]
  text = "Lorem ipsum"
  url = "/contact/"

[params.cta_secondary]
  text = "Dolor sit"
  url = "/about/"
```

## Highlights and feature cards

```toml
[[params.highlights]]
  value = "01"
  label = "Lorem ipsum dolor"

[[params.feature_cards]]
  title = "Lorem ipsum dolor"
  text = "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
```

## Social links (profile card)

```toml
[[params.social]]
  name = "Lorem"
  url = "#"
```

## Date handling

This example config uses a front matter fallback so dates never show as "0001".

```toml
[frontmatter]
  date = ["date", "publishDate", "lastmod", ":fileModTime"]
  lastmod = [":git", ":fileModTime"]
```
