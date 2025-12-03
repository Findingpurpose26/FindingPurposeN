# Complete Jekyll GitHub Pages Site Package
Below is a **fully functional GitHub Pages Jekyll website**, including:
- `_config.yml`
- `index.md`
- `about.md`
- `blog.md`
- Sample post in `_posts/`

Copy these files into your GitHub repo named:
**yourusername.github.io**

Make sure the folder structure matches exactly.

---

## 📁 `_config.yml`
```yaml
# Jekyll Configuration
name: "Jabari Aspilaire"
description: "Cybersecurity Student | Python Programmer | Networking Enthusiast"

markdown: kramdown
theme: minima

# Navigation links
header_pages:
  - about.md
  - blog.md

```

---

## 📁 `index.md`
```markdown
---
layout: home
title: Home
---

# Welcome!
Hi, I'm **Jabari Aspilaire** — a cybersecurity student with experience in Python, IPv6 networking, and system troubleshooting. I love building secure systems and learning new technologies.

Use the navigation above to explore my site.
```

---

## 📁 `about.md`
```markdown
---
layout: page
title: About
---

## About Me
I'm a cybersecurity student passionate about networking, Python development, and real-world defensive security.

Skills include:
- Python scripting
- IPv6 Networking
- Troubleshooting & diagnostics
- Technical customer service

Feel free to connect with me!

### Links
- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourusername
```

---

## 📁 `blog.md`
```markdown
---
layout: page
title: Blog
---

Below are my latest posts:

{% assign posts = site.posts %}
{% for post in posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
```

---

## 📁 `_posts/2025-01-01-welcome.md`
```markdown
---
layout: post
title: "Welcome to My New Personal Website"
date: 2025-01-01
---

This is my first post! More cybersecurity, networking, and tech write‑ups coming soon.
```

---

## ✅ Deployment Instructions
1. Go to GitHub → Create a repo named:
   **yourusername.github.io**
2. Copy **all files above** into the repo using the same folder structure:
```
/yourusername.github.io
   |_ _config.yml
   |_ index.md
   |_ about.md
   |_ blog.md
   |_ _posts/
        |_ 2025-01-01-welcome.md
```
3. Push to GitHub.
4. Visit: `https://yourusername.github.io/`

Your Jekyll site will build automatically.

---
If you want, I can also:
- Customize colors and design
- Add more posts
- Add a Projects page
- Add dark mode

Just tell me!

