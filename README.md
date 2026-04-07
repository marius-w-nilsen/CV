# Your CV - GitHub Pages Site

A minimalist, clean CV website built with Jekyll and hosted on GitHub Pages.

## Features

- ✨ Minimalist & clean design
- 🌓 Dark/Light mode toggle
- 📱 Fully responsive (mobile-friendly)
- 🚀 Fast & lightweight
- 🔍 SEO optimized
- 📄 Easy to customize with Markdown

## Setup Instructions

### 1. Initial Setup

```bash
cd CV
bundle install
```

### 2. Local Development

```bash
bundle exec jekyll serve
```

Then visit `http://localhost:4000/CV` in your browser.

### 3. Customize Your CV

Edit `index.md` with your personal information, experience, skills, and projects.

Edit `_config.yml` to update:
- `title` - Your CV title
- `author.name` - Your name
- `author.email` - Your email
- `author.github` - Your GitHub username
- `url` - Your GitHub Pages URL

### 4. Prepare for GitHub Pages

1. Create a new repository named `CV` on GitHub
2. Clone it locally (if not already done)
3. Push the contents to GitHub:

```bash
git init
git add .
git commit -m "Initial CV site"
git branch -M main
git remote add origin https://github.com/yourusername/CV.git
git push -u origin main
```

### 5. Enable GitHub Pages

1. Go to your repository settings on GitHub
2. Scroll to "GitHub Pages" section
3. Select `main` branch as source
4. Your site will be live at `https://yourusername.github.io/CV`

## Customization Tips

- **Colors**: Edit the color variables in `assets/css/style.scss`
- **Fonts**: Change the font-family in `body` selector
- **Dark Mode**: The theme toggle is automatic and saved in localStorage
- **Add Sections**: Simply add markdown headers and content to `index.md`

## Browser Support

Works on all modern browsers including:
- Chrome/Edge
- Firefox
- Safari
- Mobile browsers
