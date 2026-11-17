---
title: "Element Visibility on Mobile & Desktop"
slug: "element-visibility-on-mobile-and-desktop"
date: 2026-11-24
tags:
  - Carrd Tips
excerpt: "~Learn how to show or hide specific Carrd elements on mobile and desktop using CSS media queries, even with a Standard account.~"
---

Want to show different elements depending on whether someone visits your Carrd site on a mobile device or desktop? Even if you're using a Carrd Standard account, you can achieve this with a little custom CSS.

Add the following code to an Embed element:

```html
<style>
/* Hide Element on Desktop */
@media screen and (min-width: 736px) {
  #gallery01 {
    display: none;
  }
}

/* Hide Element on Mobile */
@media screen and (max-width: 736px) {
  #container03,
  #icons01 {
    display: none;
  }
}
</style>
```

Here's how to customize it:

- **Hide on desktop:** Replace `#gallery01` with the ID of the element you want to hide on desktop.
- **Hide on mobile:** Replace `#container03` and `#icons01` with the IDs of the elements you want to hide on mobile. You can list multiple IDs, separated by commas.

The `736px` breakpoint is a common starting point for separating mobile and desktop layouts, but you can adjust it to suit your design.

With this approach, you can create device-specific layouts without needing a higher Carrd plan.

