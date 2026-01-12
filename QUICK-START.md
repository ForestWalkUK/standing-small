# Standing-Small Jekyll Demo — Quick Start
**Version 1.0**

## What You've Got

A complete, working Jekyll website with:
- ✅ Homepage with clear vision statement
- ✅ Dedicated Gospel page (accessible from everywhere)
- ✅ Articles system (add articles by creating new .md files)
- ✅ About page with your testimony
- ✅ Sample article (Oxford Movement)
- ✅ Professional theme (clean, Reformed aesthetic)
- ✅ Free hosting ready (GitHub Pages)

---

## The 5-Minute Overview

### How Jekyll Works in Plain English

**You write:**
```
articles/my-article.md (plain text file)
```

**Jekyll transforms it into:**
```
yoursite.com/articles/my-article/ (beautiful web page)
```

**Magic? No—just simple file processing.**

---

## File Structure At-a-Glance

```
standing-small-demo/
│
├── _config.yml              ← Site settings (edit once)
├── index.md                 ← Homepage
├── gospel.md                ← Gospel page
├── articles.md              ← Articles index
├── about.md                 ← About page
│
├── _articles/               ← Put all your articles here
│   └── 2026-01-12-oxford-movement.md
│
├── _layouts/                ← HTML templates (rarely edit)
│   └── article.html
│
├── Gemfile                  ← Dependencies (don't edit)
├── README.md                ← Full instructions
└── WRITING-GUIDE.md         ← Article writing standards
```

---

## Getting Started in 3 Steps

### Step 1: Install Jekyll (One Time Only)

**Windows:**
1. Install Ruby from https://rubyinstaller.org/
2. Open Command Prompt
3. Run: `gem install jekyll bundler`

**Mac:**
1. Open Terminal
2. Run: `gem install jekyll bundler`

### Step 2: Preview Locally

1. Extract the ZIP file
2. Open Terminal/Command Prompt
3. Navigate to folder: `cd path/to/standing-small-demo`
4. Run: `bundle install` (first time only)
5. Run: `bundle exec jekyll serve`
6. Open browser: `http://localhost:4000`

**You're now viewing your site!**

### Step 3: Make Changes

1. Edit any `.md` file in a text editor
2. Save
3. Refresh browser
4. See your changes instantly

---

## Adding Your First Article

### Create the File

In `_articles/` folder, create: `2026-01-15-my-first-article.md`

### Add Front Matter

```yaml
---
layout: article
title: "My First Article"
date: 2026-01-15
category: Ecclesiastical Apostasy
excerpt: "A brief summary."
---
```

### Write Content

```markdown
# My First Article

## Introduction

Your content here in Markdown...

> *"Scripture quotation in italics"* — Reference

## Conclusion

Point to Christ.

---

*Soli Deo Gloria*
```

### See It Live

- Save the file
- Jekyll automatically rebuilds
- Go to: `http://localhost:4000/articles/my-first-article/`
- It's there!

---

## Publishing to the Internet (Free)

### Option 1: GitHub Pages (Recommended)

1. Create free GitHub account
2. Create repository called `standing-small`
3. Push your files:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR-USERNAME/standing-small.git
   git push -u origin main
   ```
4. Enable GitHub Pages in repository settings
5. Your site is live at: `https://YOUR-USERNAME.github.io/standing-small/`

**Cost: £0/year**

### Option 2: Netlify (Also Free)

1. Create account at netlify.com
2. Drag and drop your folder
3. Site is live instantly
4. Get a free subdomain: `standing-small.netlify.app`

**Cost: £0/year**

### Custom Domain (Optional)

Buy `standing-small.org.uk` (£10/year) and point it to GitHub Pages or Netlify. Full instructions in main README.

---

## Your Workflow Going Forward

### Weekly/Monthly Article Publishing

1. **Write article** in `_articles/` folder (30 minutes)
2. **Preview locally** with `jekyll serve` (2 minutes)
3. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Added article on X"
   git push
   ```
4. **Live in 30 seconds**

**Total time: 35 minutes per article.**

---

## Customising the Look

The current theme (Minima) is professional and clean. To customise:

### Change Colours/Fonts
1. Create `assets/css/style.scss`
2. Override theme variables
3. Detailed guide in main README

### Change Layout
1. Edit files in `_layouts/`
2. Modify HTML structure
3. Test locally before pushing

**Start simple. Customise gradually.**

---

## Common Questions

**Q: Do I need to know HTML/CSS?**  
A: No. Just write in Markdown. Jekyll handles the rest.

**Q: Can I write articles offline?**  
A: Yes. Write anywhere, push when you have internet.

**Q: What if I make a mistake?**  
A: Git version control means you can undo anything.

**Q: How do I add images?**  
A: Put images in `assets/images/`, reference in Markdown: `![Alt text](assets/images/photo.jpg)`

**Q: Can I add more pages?**  
A: Yes. Create new `.md` files in root, add to navigation in `_config.yml`.

**Q: Is this really free?**  
A: Yes. GitHub Pages is free forever for public repositories.

---

## What's Included

### Pages
- ✅ Homepage (compelling introduction)
- ✅ Gospel page (comprehensive salvation explanation)
- ✅ Articles index (automatic list generation)
- ✅ About page (your testimony and vision)

### Sample Content
- ✅ One complete article (Oxford Movement)
- ✅ Front matter examples
- ✅ Scripture formatting
- ✅ Gospel applications

### Documentation
- ✅ README (full technical guide)
- ✅ WRITING-GUIDE (article standards)
- ✅ This quick start guide

### Infrastructure
- ✅ Jekyll configuration
- ✅ Article collection system
- ✅ Navigation menu
- ✅ Mobile responsive
- ✅ RSS feed ready
- ✅ SEO optimised

---

## Next Steps

1. **Extract the ZIP** to your computer
2. **Read README.md** for full setup instructions
3. **Preview locally** to see how it works
4. **Experiment** by editing files
5. **Write your first article** when ready
6. **Deploy to GitHub Pages** to go live

---

## Support

If you get stuck:
- Check README.md (comprehensive)
- Jekyll docs: https://jekyllrb.com/docs/
- GitHub Pages guide: https://pages.github.com/

---

## Remember

This isn't just a website—it's a platform for:
- Exposing error
- Defending truth
- Exalting Christ

Write with:
- **Accuracy** (get facts right)
- **Clarity** (make truth accessible)
- **Charity** (love your reader)
- **Dependence** (pray continually)

> *"For other foundation can no man lay than that is laid, which is Jesus Christ."* — 1 Corinthians 3:11

---

**You're ready.** By God's grace, standing small.

*Soli Deo Gloria*

---

**Version 1.0** — 12 January 2026
