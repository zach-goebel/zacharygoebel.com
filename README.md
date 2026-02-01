# zacharygoebel.com

Personal site for Zach Goebel, built with Jekyll and deployed on GitHub Pages.

## Run locally

1. Install Ruby and Bundler.
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Start the local server:
   ```bash
   bundle exec jekyll serve
   ```
4. Visit `http://localhost:4000`.

## Add a blog post

Create a new Markdown file in `_posts/` using the format `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "Your Post Title"
---
Your content here.
```

Posts automatically appear on `/blog`.

## Set a custom domain in GitHub Pages

1. In your GitHub repo, go to **Settings → Pages**.
2. Under **Custom domain**, enter `zacharygoebel.com` and save.
3. Update your DNS provider with the required `A` or `CNAME` records from GitHub.
4. Ensure the `url` value in `_config.yml` matches your domain.
