---
title: Getting Started with Your Carrd Blog
slug: getting-started-with-carrd-blog
date: 2026-11-03
cover: "https://widget-tip.carrd.co/assets/images/image01.svg?v=65f1d69e"
excerpt: Set up your own blog with GitHub and Carrd in just a few minutes. Follow this simple guide to get your articles published on your website.
---

![img](https://widget-tip.carrd.co/assets/images/image02.png?v=9b80c83e){width=100px round=50%} [^codemefinn^]{#999999}  

## Getting Started

Before we begin, you'll need **Carrd Pro Standard or higher**, as this setup uses Carrd's Embed element.
Don't worry if you've never used GitHub before. You don't need any coding experience to get your blog up and running.

### 1. Create Your Blog Repository

First, you'll need a [GitHub account](https://github.com/).
What is GitHub? It's a platform where millions of developers store and manage their code. But you don't have to be a developer to use it. GitHub is also a great place to organize and manage your blog articles.

Once you've signed up, let's get your blog template.
Visit my GitHub profile [@codemefinn](https://github.com/codemefinn) and find the `carrd-blog-template` repository.

Open it and click the green **Use this template** button in the upper-right corner. Then select **Create a new repository**.
Choose a name for your repository. We recommend using lowercase letters and hyphens (`-`) to keep things simple.

Finally, click **Create repository**.
That's it! Your blog's content storage is ready.

### 2. Manage Your Articles

Once your repository is created, this is where you'll create and manage your articles.

You'll find a README file with instructions on how to write and publish your posts. Articles are written in Markdown, a simple writing format that's easy to learn.
If you're already familiar with Carrd's text editor, you'll probably find this even easier.

You can create, edit, and manage your articles directly on GitHub, whether you're using a computer or your phone.
For now, you can simply take a look at the instructions. You can come back to this later.

### 3. Display Your Blog on Carrd

Now for the fun part!

Start with the [Carrd Blog Template](https://carrd.com/build/6361659118c1e589) I've prepared for this guide.
At the top of the template, find the **Embed Config** code.
You'll need to update two attributes:

- `data-owner="codemefinn"` — replace `codemefinn` with your GitHub username.
- `data-repo="pk-blog-public"` — replace `pk-blog-public` with the name of the repository you just created.

Next, find the Gallery element inside the blog section.
You can upload an image to use as a loading placeholder while your articles are being loaded. Feel free to choose any image for now — you can always change it later.

Once everything is set up, publish your Carrd website.
Your GitHub articles should now appear on your website automatically!

### 4. Customize Your Blog

Want to make your blog fit your website perfectly?
There are a few additional configuration options you can adjust in the Embed Config:
- `data-posts-per-page` — Number of articles displayed per page.
- `data-articles-section` — Carrd section ID for your article list.
- `data-article-section` — Carrd section ID for individual articles.
- Other element IDs — The Carrd element IDs used for displaying article titles, dates, and content.
You can customize these settings to match your own Carrd layout. If you're already familiar with Carrd's elements and IDs, you'll know exactly what to do.

And that's it!
Your blog is now connected to GitHub, and publishing new articles is as simple as editing a file.

More features are on the way as we continue improving the experience.
Stay tuned and follow PK on X for updates!
