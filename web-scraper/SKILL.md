---
name: web-scraper
description: Fetch and extract readable text from any web page. Use for reading articles, checking website content, extracting data, and accessing information behind URLs.
---

# Web Scraper

Fetch any web page and extract its readable text content. Strips out navigation, ads, scripts, and formatting to give you clean text.

## How to Use

```json
{
  "url": "https://example.com/article",
  "max_chars": 5000
}
```

## Features
- Strips HTML, scripts, styles, navigation, headers, footers
- Returns clean readable text
- Falls back to direct fetch if CORS proxy unavailable
- Configurable max character limit

## Use Cases
- Read news articles behind URLs
- Extract data from web pages
- Check website content
- Fetch documentation or reference material
- Get current information from any public webpage

## Limitations
- JavaScript-rendered pages may return empty content
- Some sites block automated access
- Maximum ~5000 characters returned to preserve context
