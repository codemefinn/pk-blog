---
title: "Set Tooltip for Desktop Devices"
slug: "set-tooltip-for-desktop-devices"
date: 2026-11-22
tags:
  - Carrd Tips
excerpt: "~Learn how to add a simple hover tooltip to Carrd elements using JavaScript or custom attributes.~"
---

Want to show a little extra information when someone hovers over an element on your Carrd site? You can use the HTML `title` attribute to create a simple tooltip on desktop devices.

For example:

```javascript
const element = document.querySelector('#text38');
element.setAttribute('title', 'Tooltip content goes here...');
```

Here's how it works:

1. **Select the element:** `document.querySelector('#text38')` finds the element with the ID `text38` and stores it in the variable `element`.
2. **Set the tooltip:** `setAttribute('title', '...')` adds a `title` attribute with your chosen tooltip text.
3. **Display the tooltip:** Most desktop browsers automatically show the tooltip when visitors hover over the element.

**Another option:** If you have Carrd Pro Plus, you can add the attribute directly in the element's settings (gear icon). For example, enter `title=Your tooltip content` in the attributes field.

Keep in mind that browser tooltips are generally designed for mouse hover, so they may not appear the same way on touch devices.
