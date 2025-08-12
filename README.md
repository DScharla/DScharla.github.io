# 4th Semester Learning Log (GitHub Pages + Jekyll)

Weekly blog for: Goal → How I learned → What I learned → What I built → Reflection.

## Quick start
1. Create a repo named `YOURUSER.github.io` (public).
2. Copy these files into the repo.
3. Commit to the `main` branch.
4. Go to **Settings → Pages** and ensure "GitHub Actions" is selected as the build source.
5. Your site will publish at `https://YOURUSER.github.io/` after the workflow runs.

## Add a week
- Create a file in `_posts` named `YYYY-MM-DD-week-XX-topic.md` with this front matter:

```yaml
---
layout: post
title: Week XX — [Topic]
week: XX
tags: [tag1, tag2]
goal: ""
how: |
  - 
learned: |
  - 
built: |
  - 
outcome: ""
reflection: |
  - 
links: |
  - 
---
```

## Optional local preview
```bash
gem install jekyll bundler jekyll-seo-tag jekyll-feed
bundle exec jekyll serve
```
