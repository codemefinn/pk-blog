---
title: "Code Block Embed Position"
slug: "code-block-embed-position"
date: 2026-11-17
excerpt: "~Where to place CSS, JavaScript, and HTML when adding custom code to Carrd.~"
tags:
  - Carrd Tips
---

When adding custom code to your Carrd site, it's important to place each type of code in the right spot. In an Embed element, choose the following positions:

- **HTML contents** — Set the Embed Position to **Inline**.
- **CSS (`<style> ... </style>`)** — Set the Embed Position to **Head**.
- **JavaScript (`<script> ... </script>`)** — Choose the Embed Position based on when the script needs to run:
  - **Head** — Runs early, before the page body is parsed. Suitable for scripts that need to initialize settings, define global variables, or configure behavior before the page content loads. Consider using `defer` if the script needs to access DOM elements.
  - **Body Top** — Runs near the beginning of the body, before most page content is parsed. Useful when the script needs to execute early but should run after the head.
  - **Body End** — Runs near the end of the body, after most page content has been parsed. Generally recommended for scripts that need to access page elements.

Choosing the right position helps ensure your code works as expected.

