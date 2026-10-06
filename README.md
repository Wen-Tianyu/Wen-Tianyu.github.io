# wen-tianyu.github.io

Personal website of Tianyu Wen, built with [Academic Pages](https://github.com/academicpages/academicpages.github.io) (Jekyll) and hosted on GitHub Pages.

## Where things live

| What | File(s) |
|---|---|
| Sidebar (name, avatar, links) and site settings | `_config.yml` |
| Top navigation | `_data/navigation.yml` |
| Home page (bio, news) | `_pages/about.md` |
| CV | `_pages/cv.md` |
| Publications | `_publications/*.md` (one file per paper) |
| Blog posts | `_posts/YYYY-MM-DD-slug.md` |
| Travel map and city list | `_data/travel.yml` |
| Travel photo pages | `_travel/*.md` |
| Images | `images/` |
| Custom styles | `_sass/layout/_custom.scss` |

## Common edits

**New blog post**: create `_posts/2026-10-05-my-post.md`:

```markdown
---
title: "标题"
tags:
  - 随笔
---

正文……
```

**New travel city**: put the photos in `images/<City>/`, copy any file in `_travel/` as a template, and add the city (with `page:` set to the file name) to `_data/travel.yml`.

**New paper**: copy a file in `_publications/` and edit its front matter.

Resize photos before adding them (around 1600px wide is enough), for example on macOS:

```bash
sips -Z 1600 -s formatOptions 75 images/NewCity/*.jpg
```

## Run locally

Requires Ruby 3.x:

```bash
bundle install
bundle exec jekyll serve -l
```

Then open http://localhost:4000. Pushing to `main` publishes the site automatically.
