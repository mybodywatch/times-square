# MyBodyWatch Times Square Content Repository Guide

## Repository Purpose
This repository serves as a lightweight CMS for the MyBodyWatch app's Library feature, containing clean markdown articles and metadata.

## Content Structure Philosophy
- **JSON as single source of truth** - All metadata (title, summary, category, dates, images) lives in index.json
- **Clean markdown content** - Articles contain only body content, no frontmatter or duplicate titles/images
- **App displays JSON metadata** - Title and header image from JSON, content from markdown
- **Minimal client parsing** - App is "dumb", content repo is "smart"

## Content Guidelines
- Start articles directly with body content (no H1 titles)
- No YAML frontmatter (metadata goes in index.json)
- No header images in markdown (use JSON imageURL)
- Use clear, concise language for all articles
- Follow proper Markdown formatting for H2+ headings
- Keep article lengths appropriate for mobile viewing
- Organize content in appropriate category folders

## File Management
- Update index.json when adding new articles
- Store images in /images directory (referenced via JSON imageURL)
- Use descriptive filenames: descriptive-name-with-hyphens.md
- Ensure contentURL in JSON matches actual file path

## JSON Metadata Structure
Each article entry in index.json should include:
```json
{
  "id": "unique-article-id",
  "title": "Article Title (displays in app header)",
  "summary": "Brief description for card view",
  "category": "getting_started|features|science|techniques",
  "publishDate": "2025-03-08T00:00:00Z",
  "contentURL": "https://raw.githubusercontent.com/mybodywatch/times-square/main/articles/category/filename.md",
  "imageURL": "https://images.unsplash.com/... or local image URL",
  "featured": true/false,
  "version": "1.0"
}
```