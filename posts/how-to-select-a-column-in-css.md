---
title: "How to Select a Column in CSS"
slug: "how-to-select-a-column-in-css"
date: 2026-11-20
tags:
  - Carrd Tips
excerpt: "~Learn how to target a specific column inside a Carrd container using CSS selectors.~"
---

You can use CSS selectors to target individual columns within a Carrd container. This is useful when you want to apply custom styles to a specific column without affecting the others.

For example, the following selector targets the second column inside `#container22`:

```css
#container22 > .wrapper > .inner > :nth-child(2) {
  /* Add your styles here */
}
```

To target a different column, simply change the number in `:nth-child()`. You can also replace `#container22` with the ID of another container.

This gives you more control over individual columns and makes it easier to customize your Carrd layouts with CSS.
