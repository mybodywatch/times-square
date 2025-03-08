# MyBodyWatch Times Square Content Repository Guide

## Repository Purpose
This repository contains content for the MyBodyWatch app's news feed, organized as markdown articles and supporting images.

## Content Guidelines
- Use clear, concise language for all articles
- Include relevant images when they enhance understanding
- Follow proper Markdown formatting practices
- Ensure proper spelling and grammar
- Organize content in appropriate category folders (features, news, tips, getting-started)
- Filename format: descriptive-name-with-hyphens.md

## Content Management
- Update index.json when adding new articles
- Store images in the /images directory with descriptive filenames
- Reference images using relative paths: `![Alt text](../images/filename.jpg)`
- Keep article lengths appropriate for mobile viewing

## Metadata Format
Articles should include front matter metadata in YAML format:
```yaml
---
title: "Article Title"
date: "YYYY-MM-DD"
author: "Author Name"
featured: true/false
---
```