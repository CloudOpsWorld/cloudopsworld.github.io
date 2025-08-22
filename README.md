# Jekyll Markdown Blog Starter (for GitHub Pages)

A minimal, theme-free Jekyll setup that turns Markdown files in `_posts/` into blog posts.
- No Ruby install required locally — GitHub Pages builds it for you.
- Clean HTML/CSS you can customize in `assets/style.css`.
- Includes RSS feed and SEO tags via official plugins.

## Quick start
1. Create a repo named `USERNAME.github.io` (replace `USERNAME`).
2. Upload these files to the repo root and commit.
3. In **Settings → Pages**, choose **Deploy from a branch**, **main**, **/**.
4. Visit `https://USERNAME.github.io`.
5. Add posts in `_posts/YYYY-MM-DD-title.md` with front matter:
   ```md
   ---
   layout: post
   title: "My Post"
   date: 2025-08-23
   tags: [notes]
   ---
   Hello world!
   ```
6. Customize colors in `assets/style.css` (change the `--accent` etc.).
