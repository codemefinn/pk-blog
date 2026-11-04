---
title: "Set Up Your PK Blog"
slug: setup-pk-blog
date: 2026-11-04
cover: "https://widget-tip.carrd.co/assets/images/image01.svg?v=65f1d69e"
excerpt: Get your blog up and running on Carrd with GitHub and PK Blog. Follow this step-by-step guide to set up your repository, connect your website, and publish your first article.
---

## Getting Started
Before we begin, you'll need **Carrd Pro Standard or higher**, as this setup uses Carrd's Embed element.
And don't worry if you've never used GitHub before. You don't need any coding experience to get your blog up and running.

### 1. Create Your Blog Repository
First, you'll need a [GitHub account](https://github.com/).
Once you've signed up, it's time to get the PK Blog template.

Visit my GitHub profile [@codemefinn](https://github.com/codemefinn) and find the `carrd-blog-template` repository.
Open the repository and click the green **Use this template** button in the upper-right corner. Then select **Create a new repository**.

Choose a name for your repository. We recommend using lowercase letters and hyphens (`-`) to keep it simple and easy to read. Make sure to set the repository visibility to **Public**.

Finally, click **Create repository**.
That's it! Your blog repository is ready.

### 2. Manage Your Articles
Once your repository is created, GitHub will take you to your new repository. This is where you'll create and manage your blog articles.

You'll find a `README.md` file with instructions on how to write and publish your posts. Articles are written in Markdown.
If you're already familiar with Carrd's text editor, you'll probably find Markdown just as easy to work with.

You can create, edit, and manage your articles directly on GitHub, whether you're using a computer or your phone. GitHub also offers a mobile app, so you can manage your content on the go.

For now, feel free to take a look at the instructions. You can always come back to them when you're ready to publish your first article.

### 3. Display Your Blog on Carrd
Now for the fun part!

Start with the [PK Blog Template](https://carrd.com/build/6361659118c1e589) I've prepared for this guide.
At the top of the template, find the **Embed Config** code.
You'll need to update two attributes:

- `data-owner="GITHUB_USER_NAME"` — replace `GITHUB_USER_NAME` with your GitHub username.
- `data-repo="GITHUB_REPO_NAME"` — replace `GITHUB_REPO_NAME` with the name of the repository you just created.

Next, find the Gallery element inside the blog section.
You can upload an image to use as a loading placeholder while your articles are being loaded. Feel free to choose any image for now — you can always change it later.

Once everything is set up, save and publish your Carrd website.
Your GitHub articles should now appear on your website automatically!

### 4. Customize Your Blog
Want to make your blog fit your website perfectly?
There are a few additional configuration options you can adjust in the Embed Config:

- `data-posts-per-page` — Number of articles displayed per page.
- `data-pagination` — Carrd element ID for the pagination controls.
- `data-articles-section` — Carrd section ID for the article list.
- `data-article-section` — Carrd section ID for an individual article.
- **Other element IDs** — Carrd element IDs used to display article titles, publication dates, and content.
  
You can customize these settings to match your own Carrd layout. If you're already familiar with Carrd's elements and IDs, you'll know exactly what to do.

And that's it. Your blog is now connected to GitHub, and publishing new articles is as simple as editing a file.

More features are on the way as we continue improving the experience.
Stay tuned and follow PK on [X](https://twitter.com/Plugin_Kitchen) for updates.
