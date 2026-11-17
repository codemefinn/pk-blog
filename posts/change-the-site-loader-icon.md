---
title: "Change the Site Loader Icon"
slug: "change-the-site-loader-icon"
date: 2026-11-28
tags:
  - Carrd Tips
excerpt: "~Customize Carrd's default loading screen with your own icon using a simple CSS snippet.~"
---

Want your site to feel a little more personal, even while it's loading? You can replace Carrd's default loader with an icon of your choice using a small CSS snippet.

Add the following code to an **Embed** element and set its position to **Head**. Remember to replace the URL with your own icon image URL.

```html
<style>
#loader {
  background-image: url(https://your-icon-url-here) !important;
}
</style>
```

You can also combine this with the **Spin-3D** widget to create a more interesting loading effect.

It's a small detail, but it helps carry your site's visual style right from the moment someone visits.
