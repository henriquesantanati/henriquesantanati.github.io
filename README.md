# Henrique Santana's Personal Website

Personal website built with Jekyll and hosted on GitHub Pages.

## Local Development

### Prerequisites
- Ruby 2.7+ (check with `ruby --version`)
- Bundler (install with `gem install bundler`)

### Setup
```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# View at http://localhost:4000
```

## Creating Content

### Blog Posts
Create files in `_posts/` with format: `YYYY-MM-DD-title.md`

Example frontmatter:
```yaml
---
layout: post
title: "My Blog Post Title"
date: 2026-02-15 21:30:00 -0800
categories: tech aws
tags: [containers, kubernetes, eks]
---
```

### Drafts
Put work-in-progress posts in `_drafts/` (no date required in filename).

View drafts locally: `bundle exec jekyll serve --drafts`

### Pages
Create `.md` files in the root directory with frontmatter:
```yaml
---
layout: page
title: Page Title
permalink: /page-url/
---
```

## Deployment

GitHub Pages automatically builds and deploys when you push to `main` branch.

## Customization

- Edit `_config.yml` for site-wide settings
- Modify layouts in `_layouts/` (if needed)
- Add custom CSS in `assets/css/`
- Theme documentation: [Minima](https://github.com/jekyll/minima)

## License

Content is © Henrique Santana. Code is MIT licensed.
