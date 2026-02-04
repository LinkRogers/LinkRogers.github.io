# SaxLee's Personal Page

This is a Jekyll-based personal website for Shi Li, a software engineer at SAIC MOTOR INC., hosted on GitHub Pages.

## 📖 Documentation | 文档

- **[English Documentation](#english-documentation)** - How this site works and how to modify it
- **[中文文档](README-CN.md)** - 网站工作原理和修改指南

---

## English Documentation

### What is this?

This is a personal homepage built with **Jekyll** and hosted on **GitHub Pages**. It's completely free and automatically updates whenever you push changes to this repository.

- **Live Site**: https://LinkRogers.github.io/
- **Technology**: Jekyll (Static Site Generator)
- **Hosting**: GitHub Pages (Free)

### Quick Start Guide

#### 1. Modify Basic Information

Edit `_config.yml` to change site-wide settings:

```yaml
title: Shi Li                              # Site title
email: shili@saicmotor.com                 # Contact email
description: "Your bio here..."            # Site description
url: "http://LinkRogers.github.io/"       # Site URL
github_username: LinkRogers                # GitHub username
```

#### 2. Edit Page Content

- **Homepage**: Edit `index.md`
- **About**: Edit `about.md`
- **CV**: Edit `CV.md`
- **Research**: Edit `research.md`
- **Projects**: Edit `project.md`

Each file has YAML front matter at the top:

```markdown
---
layout: page              # Layout template to use
title: Page Title         # Page title
permalink: /about/        # URL path
weight: 6                 # Navigation order (lower = earlier)
---

Your content here...
```

#### 3. Add Images

1. Upload images to the `pics/` folder
2. Reference them in Markdown: `![Alt text](/pics/image.jpg)`

#### 4. Publish Changes

```bash
git add .
git commit -m "Describe your changes"
git push origin main
```

Changes will appear on your site in 1-2 minutes.

#### 5. Local Testing (Optional)

```bash
# Install Jekyll
gem install jekyll bundler

# Run local server
jekyll serve

# Visit http://localhost:4000
```

### Site Structure

```
LinkRogers.github.io/
├── _config.yml          # Global site configuration
├── index.md             # Homepage content
├── about.md             # About page
├── CV.md                # CV page
├── research.md          # Research page
├── project.md           # Projects page
├── _layouts/            # Page layout templates
├── _includes/           # Reusable components
├── _sass/               # Sass stylesheets
├── css/                 # CSS files
└── pics/                # Images
```

### Learn More

- [Jekyll Documentation](https://jekyllrb.com/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)

---

**For detailed Chinese documentation, see [README-CN.md](README-CN.md)**
