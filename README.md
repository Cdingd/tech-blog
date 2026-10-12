# tech-blog

Hugo + GitHub Pages 技术博客。主题为自带的极简布局，不依赖外部主题与子模块。

## 目录结构

1. 文章：`content/posts/<slug>.md`
2. 布局：`layouts/`（自带的极简模板）
3. 样式：`static/css/style.css`
4. 构建：`.github/workflows/hugo.yml`

## 文章 frontmatter

只写四个字段：

```yaml
---
title: "标题"
date: 2026-10-12
tags: ["Hugo"]
author: "Cdingd"
---
```

## 发布流程

1. 新文章放 `content/posts/` 下
2. 提 PR
3. 合并到 main 后由 GitHub Actions 自动构建并部署

## 本地预览

```bash
hugo server -D
```
