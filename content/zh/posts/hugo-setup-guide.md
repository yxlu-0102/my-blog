---
title: "如何用 Hugo 和 PaperMod 搭建这个博客"
date: 2026-03-25T10:00:00+08:00
draft: false
tags: ["hugo", "教程", "网站"]
categories: ["教程"]
summary: "一步步介绍如何使用 Hugo 静态网站生成器和 PaperMod 主题搭建个人博客。"
ShowToc: true
TocOpen: true
---

## 为什么选择 Hugo？

Hugo 是最受欢迎的静态网站生成器之一。它速度极快、主题支持丰富、部署简单。搭配 PaperMod 主题，开箱即用就能获得一个简洁、现代、功能齐全的博客。

## 前置条件

开始之前，确保你已经安装了：

1. [Hugo](https://gohugo.io/installation/)（推荐安装 extended 版本）
2. [Git](https://git-scm.com/)
3. 任意一个你喜欢的文本编辑器

## 开始搭建

### 创建新的 Hugo 站点

```bash
hugo new site my-blog
cd my-blog
git init
```

### 添加 PaperMod 主题

```bash
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
```

### 配置站点

编辑 `hugo.toml` 来配置你的站点设置、主题和菜单项。

## 写第一篇文章

创建新文章：

```bash
hugo new posts/my-first-post.md
```

然后编辑生成的文件，写入你的内容。

## 本地预览

运行开发服务器：

```bash
hugo server -D
```

访问 `http://localhost:1313` 查看你的网站！

## 部署

你可以将 Hugo 网站部署到 GitHub Pages、Netlify 或 Vercel 等平台。我推荐 GitHub Pages，因为它简单且免费。

## 总结

Hugo + PaperMod 是搭建个人博客的绝佳组合。它快速、可定制、易于维护。祝你写博客愉快！
