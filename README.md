# Beyond the Meter

> Reflections from the intersection of energy, governance, and technology

Personal blog by [Prudhvi](https://prudhvitejimmadi.github.io)

---

## Local Development

### Prerequisites
- Ruby 3.x
- Bundler

### Setup

```bash
# Install dependencies
bundle install

# Run locally
bundle exec jekyll serve

# Open in browser
open http://localhost:4000
```

---

## Writing a New Post

Create a new file in `_posts/` following this naming convention:

```
_posts/YYYY-MM-DD-your-post-title.md
```

Add this front matter at the top:

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
categories: [category1, category2]
tags: [tag1, tag2]
author: Prudhvi
---

Your content here...
```

Then push to GitHub:

```bash
git add .
git commit -m "New post: Your Post Title"
git push
```

Your post will be live at `prudhvitejimmadi.github.io` within a minute.

---

## Deployment

This blog is hosted on GitHub Pages. Every push to the `main` branch triggers an automatic build and deploy.

---

*Built with [Jekyll](https://jekyllrb.com) and hosted on [GitHub Pages](https://pages.github.com)*
