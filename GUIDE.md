# Portfolio Editing Guide

This guide will help you understand how to edit your portfolio code.

## Project Structure

```
Tportfolio/
├── _config.yml           # Site configuration
├── _layouts/             # HTML templates
│   ├── default.html      # Main layout template
│   └── project.html      # Project page template
├── _projects/            # Your portfolio projects
│   ├── example-project-1.md
│   └── example-project-2.md
├── assets/
│   └── css/
│       └── custom.css    # Custom site styling
├── index.md              # Homepage
├── about.md              # About page
└── README.md             # Repository description
```

## How to Edit Your Portfolio

### 1. Edit Site Information

Edit `_config.yml` to update:
- Site title
- Description
- Author name

### 2. Add New Projects

To add a new project:
1. Create a new file in `_projects/` folder (e.g., `my-awesome-project.md`)
2. Use this template:

```markdown
---
title: My Project Name
description: Brief project description
technologies:
  - Technology 1
  - Technology 2
github: https://github.com/yourusername/project
link: https://project-demo-url.com
---

## Overview

Describe your project here.

## Features

- Feature 1
- Feature 2

## What I Learned

What you learned from this project.
```

### 3. Edit the Homepage

Edit `index.md` to customize your homepage content.

### 4. Edit the About Page

Edit `about.md` to add information about yourself, your skills, education, and experience.

### 5. Customize Styling

Edit `assets/css/custom.css` to change:
- Colors
- Fonts
- Layout
- Spacing

## Common Edits

### Change Site Colors

In `assets/css/custom.css`, update these sections:
- `header` background-color
- Link colors (`a` tag)
- Text colors

### Change Site Title

In `_config.yml`, update the `title:` field.

### Add Your GitHub Username

Replace `yourusername` in project files and about.md with your actual GitHub username.

### Add Your Email

In `about.md`, replace `your.email@example.com` with your actual email.

## Testing Your Changes Locally

If you have Jekyll installed locally:

```bash
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

## Publishing

Your site is configured to use GitHub Pages. Once you push changes to GitHub:
1. Go to your repository settings
2. Navigate to Pages
3. Select the branch to deploy (usually `main`)
4. Your site will be available at `https://yourusername.github.io/Tportfolio/`

## Need Help?

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)
