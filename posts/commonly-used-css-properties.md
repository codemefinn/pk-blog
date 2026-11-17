---
title: "Commonly Used CSS Properties"
slug: "commonly-used-css-properties"
date: 2026-11-21
tags:
  - Carrd Tips
excerpt: "~A quick guide to commonly used CSS properties for customizing Carrd elements.~"
---

CSS properties give you control over the appearance and spacing of elements on your Carrd site. Here's a quick look at some commonly used properties and how to use them.

For example, this snippet applies several styles to the element with the ID `text01`:

```css
#text01 {
  opacity: 0.8;
  padding: 0 0 1rem 1rem;
  background-color: #216E5B;
  border: 1px solid #FFFFFF;
  border-radius: 0 0 16px 16px;
}
```

Here's what each property does:

1. **`opacity`** — Controls transparency. Values range from `0` (fully transparent) to `1` (fully opaque).
2. **`padding`** — Controls the space inside an element. Four values follow the order: top, right, bottom, left.
3. **`background-color`** — Sets the background color. You can also use a gradient instead, for example:
   ```css
   background: linear-gradient(90deg, #color1, #color2);
   ```
4. **`border`** — Combines the border width, style (such as `solid`), and color.
5. **`border-radius`** — Rounds the corners. Four values follow the order: top-left, top-right, bottom-right, bottom-left.

Try adjusting these values to see how they affect your Carrd elements. A few small changes can make a big difference in your design.
