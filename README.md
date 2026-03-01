# Henrique Santana's Personal Website

Personal website built collaboratively with AI assistance.

## About This Project

This site is built and maintained through a collaborative workflow with an AI assistant. I focus on content direction and what I want to say, while the AI handles the technical implementation.

## Tech Stack

- **Stack**: Pure HTML, CSS, and JavaScript (no framework or static site generator)
- **Hosting**: GitHub Pages
- **Fonts**: Cormorant Garant + DM Sans via Google Fonts

## Site Structure

Single-page design covering:

- **Hero**: Introduction and quick links
- **About**: Professional background
- **Expertise**: Container orchestration, AI/ML infrastructure, cloud architecture, technical leadership
- **Speaking**: Conference appearances (AWS re:Invent, KubeCon, AWS Summit)
- **Writing**: Published posts on the AWS Containers Blog
- **Connect**: LinkedIn and GitHub links

## Adding a New Blog Post

Open `index.html` and find the comment in the Writing section:

```html
<!-- ✏️ TO ADD A NEW POST: copy one writing-item block below and paste it here at the top. -->
```

Copy any `<div class="writing-item">` block, paste it at the top of the list, and update:
- `href` — link to the post
- `writing-category` — e.g. `ECS · Monitoring`
- `writing-title` — full post title
- `writing-meta` — publication name

## Live Site

🌐 **[henriquesantanati.github.io](https://henriquesantanati.github.io/)**

---

Built with ❤️ by Henrique Santana, in collaboration with AI
