# Standing-Small Jekyll Demo Site
**Version 1.0**

## What Is This?

This is a complete, working demonstration of a **Jekyll static site** for your Standing-Small project. Jekyll is a static site generator—it takes simple text files (written in Markdown) and converts them into a complete website with HTML, CSS, and proper navigation.

---

## Why Jekyll?

1. **Free hosting** on GitHub Pages (no monthly costs)
2. **Write in Markdown** (which you already know)
3. **Version controlled** with Git (never lose anything)
4. **No database** needed (fast, secure, simple)
5. **Professional results** without coding expertise
6. **Easy to update** (just add new .md files and push to GitHub)

---

## How Jekyll Works

### The Basic Concept

Jekyll uses a simple folder structure:

```
standing-small-demo/
├── _config.yml          # Site-wide settings (title, description, etc.)
├── index.md             # Your homepage
├── gospel.md            # Gospel page
├── articles.md          # Articles index page
├── about.md             # About page
├── _articles/           # Folder for all your article files
│   └── 2026-01-12-oxford-movement.md
├── _layouts/            # HTML templates for different page types
│   └── article.html
└── Gemfile              # Ruby dependencies (tells Jekyll what it needs)
```

### What Happens When You Run Jekyll

1. Jekyll reads all your `.md` files
2. It converts Markdown to HTML
3. It applies your layout templates
4. It generates a complete website in a `_site` folder
5. You upload this `_site` folder to your web host (or let GitHub do it automatically)

---

## The File Structure Explained

### `_config.yml`
This is your **site's control panel**. It contains:
- Site title ("Standing-Small")
- Your tagline
- Navigation menu items
- Build settings

**You edit this once** when setting up, then rarely touch it.

### `index.md`, `gospel.md`, `articles.md`, `about.md`
These are your **main pages**. Each has:
- **Front matter** (the bit between `---` at the top)
- **Content** (everything below the front matter)

Front matter example:
```yaml
---
layout: page
title: The Gospel
permalink: /gospel/
---
```

This tells Jekyll:
- Use the "page" layout template
- Title is "The Gospel"
- URL will be `yoursite.com/gospel/`

### `_articles/` folder
This is where you put all your article files. Each article is a separate `.md` file with:
- Date in filename: `2026-01-12-oxford-movement.md`
- Front matter specifying layout, title, category
- Your content in Markdown

### `_layouts/` folder
These are **HTML templates** that wrap around your content. For example, `article.html` adds:
- A header with the article title
- A footer with navigation back to articles
- A link to the Gospel page

You rarely need to touch these once set up.

---

## How to Use This Demo

### Step 1: Install Jekyll (One-Time Setup)

**On Windows:**
1. Download and install **RubyInstaller** from https://rubyinstaller.org/
2. During installation, check "Add Ruby to PATH"
3. Open Command Prompt and run:
   ```
   gem install jekyll bundler
   ```

**On Mac:**
Ruby is already installed. Just run:
```bash
gem install jekyll bundler
```

### Step 2: Download This Demo

Extract the files from the ZIP I'll create for you into a folder on your computer, e.g.:
```
C:\Users\Forest\standing-small-demo\
```

### Step 3: Open Terminal/Command Prompt

Navigate to the folder:
```bash
cd C:\Users\Forest\standing-small-demo
```

### Step 4: Install Dependencies

Run this once:
```bash
bundle install
```

This installs everything Jekyll needs.

### Step 5: Preview Your Site Locally

Run:
```bash
bundle exec jekyll serve
```

Then open your browser and go to:
```
http://localhost:4000
```

You'll see your site **running live on your computer**!

### Step 6: Make Changes

- Edit any `.md` file in a text editor (Notepad++, VS Code, etc.)
- Save the file
- Jekyll **automatically rebuilds** the site
- Refresh your browser to see changes

---

## Adding New Articles

To add a new article:

1. Create a new file in `_articles/` folder
2. Name it with date: `2026-02-15-my-new-article.md`
3. Add front matter:
   ```yaml
   ---
   layout: article
   title: "My Article Title"
   date: 2026-02-15
   category: Ecclesiastical Apostasy
   excerpt: "A brief summary of the article."
   ---
   ```
4. Write your content below in Markdown
5. Save the file
6. It automatically appears on your site!

---

## Deploying to GitHub Pages (Free Hosting)

### Step 1: Create a GitHub Account
Go to https://github.com and sign up (free).

### Step 2: Create a New Repository
- Click "New Repository"
- Name it: `standing-small`
- Make it Public
- Don't initialise with README

### Step 3: Push Your Site to GitHub
In your terminal/command prompt:
```bash
cd C:\Users\Forest\standing-small-demo
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/standing-small.git
git push -u origin main
```

### Step 4: Enable GitHub Pages
- Go to your repository on GitHub
- Click Settings → Pages
- Under "Source", select "main" branch
- Click Save

Your site will be live at:
```
https://YOUR-USERNAME.github.io/standing-small/
```

**Completely free. Forever.**

---

## Customising the Look

To change colours, fonts, or layout, you can:

1. Create a `_sass` folder with custom CSS
2. Override the default theme's styles
3. Create custom layouts in `_layouts/`

This is more advanced but entirely possible. For now, the default Minima theme is clean and professional.

---

## Adding a Custom Domain

If you buy a domain (e.g., `standing-small.org.uk`):

1. Add a file called `CNAME` to your repository root
2. Inside, put just your domain: `standing-small.org.uk`
3. In your domain registrar settings, point the domain to GitHub Pages

GitHub has detailed instructions for this.

---

## Workflow Summary

Your typical workflow will be:

1. **Write a new article** in Markdown (in `_articles/` folder)
2. **Preview locally** with `bundle exec jekyll serve`
3. **Commit and push** to GitHub:
   ```bash
   git add .
   git commit -m "Added new article on X"
   git push
   ```
4. **Site updates automatically** on GitHub Pages

**Time investment per article:** 30 minutes to write, 2 minutes to publish.

---

## Markdown Quick Reference

```markdown
# Heading 1
## Heading 2
### Heading 3

**Bold text**
*Italic text*

[Link text](https://example.com)

- Bullet point
- Another bullet

1. Numbered list
2. Second item

> Blockquote (for Scripture verses)

---
Horizontal line
```

---

## Need Help?

- Jekyll documentation: https://jekyllrb.com/docs/
- GitHub Pages guide: https://pages.github.com/
- Markdown guide: https://www.markdownguide.org/

---

## Version History

- **v1.0** (12 Jan 2026) — Initial demo site with homepage, Gospel page, articles system, and sample Oxford Movement article

---

**This is a complete, working website.** You can start using it today. It scales from 1 article to 1,000 articles. It's free to host. It's yours to customise.

**Ready to stand small, by God's grace?**

*Soli Deo Gloria*
