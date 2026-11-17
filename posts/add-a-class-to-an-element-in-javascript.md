---
title: "Add a Class to an Element in JavaScript"
slug: "add-a-class-to-an-element-in-javascript"
date: "~2026-11-17~"
tags:
  - Carrd Tips
excerpt: "~Learn how to add a CSS class to a Carrd element when it's clicked using JavaScript.~"
---

You can use JavaScript to add a CSS class to a Carrd element in response to a click.

Assuming you've already selected the icon element and stored it in the `icon` variable, use:

```javascript
icon.addEventListener('click', () => {
  icon.classList.add('rotate');
});
```

Here's how it works:

1. `addEventListener('click', ...)` listens for clicks on the icon.
2. `classList.add('rotate')` adds the `rotate` class to the element when it's clicked. You can then use CSS to define the rotation effect.

**Tip:** If you want the icon to respond to clicks without opening a link, enter `browser:none` in the element's **URL** field in Carrd.
