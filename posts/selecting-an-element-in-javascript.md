---
title: "Selecting an Element in JavaScript"
slug: "selecting-an-element-in-javascript"
date: 2026-11-17
tags:
  - Carrd Tips
excerpt: "~Learn how to select a Carrd element by its ID and use it in your JavaScript code.~"
---

To work with a Carrd element in JavaScript, you first need to select it using its ID.

```javascript
const icon = document.getElementById('icons01');
```

Here's what this line does:

1. **Selects the element:** `document.getElementById('icons01')` finds the element with the ID `icons01`. You can find or change an element's ID in its **Settings** (gear icon) in Carrd.
2. **Stores the element:** The selected element is assigned to the variable `icon`. You can then use `icon` to access and manipulate that element in your JavaScript code.
