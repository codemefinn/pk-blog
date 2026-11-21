---
title: "PK Blog 1.1.1 — Changelog & Upgrade Guide"
slug: "pk-blog-1-1-1"
date: 2026-11-19
excerpt: "~What's new in PK Blog 1.1.1 and how to upgrade from version 1.0.1.~"
pin: true
tags: 
  - PK Blog
---

# PK Blog 1.1.1

PK Blog 1.1.0 introduces several new features, including scheduled publishing, tag filtering, pinned posts, copy blocks, and improved article navigation.

## What's New

### Automatic Features
- **Scheduled Publishing** — Posts with a future `date` are automatically hidden from your Carrd website until their scheduled date. Dates use UTC.
- **Dynamic Site Title & Description** — When an individual article is loaded, the site title and description are automatically updated using the article's title and excerpt.
- **Previous & Next Posts** — Links to the previous and next articles are automatically added at the end of each article.

### Optional Frontmatter
- **Tags** — Add multiple tags to each post to organize content and enable tag filtering.
- **Pinned Posts** — Pin important articles to keep them at the top of your article list.

### Additional Features
- **Copy Blocks** — Code blocks now include a copy button. You can also specify a language name after the opening backticks as usual. Syntax highlighting is not currently supported, but this does not affect the copy functionality.
  ```
  Like this.
  ```
- **Open in New Tab** — Hold `Ctrl` (Windows/Linux) or `⌘ Cmd` (macOS) while clicking an article to open it in a new tab.

## How to Upgrade from v1.0.1
If you're currently using PK Blog v1.0.1, follow these steps to upgrade to v1.1.1.

1. Open your PK Blog config in Carrd and change the version number to `1.1.1`.

2. Add a new **Links** element to your Carrd page and assign it an ID.

3. Add `data-tags="linksID"` to your PK Blog config, replacing `linksID` with the ID of the Links element you created.

4. Set the link label to **All articles** (or the equivalent in your preferred language).

That's it. Your blog is now ready to use the new tag filtering feature.  
For full syntax and formatting details, see the [What's New in v1.1.1](https://github.com/codemefinn/pk-blog-template#whats-new-in-v111) section in the PK Blog Template README.
