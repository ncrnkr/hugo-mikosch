# Home

The home page is configured through site parameters in your config file (config.toml). The layout is built from a hero section, optional highlights, optional feature cards, and the latest posts list.

## Required params

These keep the hero readable and are used across the theme.

```toml
[params]
  subtitle = "Lorem ipsum dolor sit amet"
  tagline = "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
  hero_title = "Lorem ipsum dolor sit amet"
  hero_intro = "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
  profile_image = "/images/hero-placeholder.svg"
```

## Optional params

Use these to customize the home layout without editing templates.

```toml
[params]
  hero_kicker = "Lorem ipsum"
  hero_image = "/images/hero-placeholder.svg"
  feature_title = "Lorem ipsum"
  feature_intro = "Lorem ipsum dolor sit amet"
  posts_title = "Lorem ipsum"
  posts_intro = "Lorem ipsum dolor sit amet"

[params.cta_primary]
  text = "Lorem ipsum"
  url = "/contact/"

[params.cta_secondary]
  text = "Dolor sit"
  url = "/about/"

[[params.highlights]]
  value = "01"
  label = "Lorem ipsum dolor"

[[params.feature_cards]]
  title = "Lorem ipsum dolor"
  text = "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
```

## Notes

- If a field is missing, the theme falls back to defaults where possible.
- The Latest Posts section is driven by content in content/posts/.
