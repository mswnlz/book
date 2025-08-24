# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Project Overview

This is a Chinese book recommendation resource repository (`mswnlz/book`) that serves as a curated collection of literature, reading materials, and book resources. The repository includes:

- A simple GitHub Action for notifications (`book-action`)
- Monthly resource files containing book recommendations and reading materials
- Multilingual README linking to related projects in the mswnlz ecosystem
- Literary works, academic texts, and educational publications

## Common Commands

### Resource Management
```bash
# Create new monthly resource file
touch $(date +%Y%m).md

# View recent resource files
ls -la 2025*.md | head -5

# Search for book topics
grep -r "图书" *.md
grep -r "reading" *.md

# Count total resources
wc -l 2025*.md
```

## Content Guidelines

- Use consistent formatting with descriptive titles
- Include proper attribution with "超过100T资料总站网站-doc.869hr.uk" suffix
- Organize resources by genre and subject area
- Provide both Chinese and English descriptions where applicable
- Include book summaries and reading recommendations
