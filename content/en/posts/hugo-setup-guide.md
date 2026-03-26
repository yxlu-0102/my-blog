---
title: "How I Built This Blog with Hugo and PaperMod"
date: 2026-03-25T10:00:00+08:00
draft: false
tags: ["hugo", "tutorial", "web"]
categories: ["tutorial"]
summary: "A step-by-step guide on how I set up this personal blog using Hugo static site generator with the PaperMod theme."
ShowToc: true
TocOpen: true
---

## Why Hugo?

Hugo is one of the most popular static site generators. It's incredibly fast, has great theme support, and is easy to deploy. Combined with the PaperMod theme, you get a clean, modern, and feature-rich blog right out of the box.

## Prerequisites

Before you start, make sure you have:

1. [Hugo](https://gohugo.io/installation/) installed (extended version recommended)
2. [Git](https://git-scm.com/) installed
3. A text editor of your choice

## Getting Started

### Create a new Hugo site

```bash
hugo new site my-blog
cd my-blog
git init
```

### Add PaperMod theme

```bash
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
```

### Configure your site

Edit `hugo.toml` to configure your site settings, theme, and menu items.

## Writing Your First Post

Create a new post:

```bash
hugo new posts/my-first-post.md
```

Then edit the generated file with your content.

## Local Preview

Run the development server:

```bash
hugo server -D
```

Visit `http://localhost:1313` to see your site!

## Deployment

You can deploy your Hugo site to various platforms like GitHub Pages, Netlify, or Vercel. I recommend GitHub Pages for its simplicity and free hosting.

## Conclusion

Hugo + PaperMod is a great combination for building a personal blog. It's fast, customizable, and easy to maintain. Happy blogging!
