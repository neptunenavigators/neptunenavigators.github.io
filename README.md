# Neptune Navigators Website

Official website for Neptune Navigators - AI-powered autonomous inspection systems.

## 🚀 Quick Start

This site is built with Jekyll and hosted on GitHub Pages.

### Prerequisites
- GitHub account with `neptunenavigators` organization

### Deployment Instructions

1. **Create a new repository** in the `neptunenavigators` organization:
   - Name: `neptunenavigators.github.io` (must match exactly)
   - Visibility: Public
   - Do NOT initialize with README

2. **Push this code to the repository:**

```bash
cd /path/to/neptunenavigators-site
git init
git add .
git commit -m "Initial commit: Neptune Navigators website"
git branch -M main
git remote add origin https://github.com/neptunenavigators/neptunenavigators.github.io.git
git push -u origin main
```

3. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
   - Click Save

4. **Wait 2-3 minutes** for GitHub to build and deploy

5. **Visit your site:**
   - URL: https://neptunenavigators.github.io

## 📝 Customization

### Update Content
Edit `index.html` to change:
- Team member information
- Project descriptions
- Contact details

### Change Styling
Edit `assets/css/style.css` for visual customization.

### Add Custom Domain (Optional - Later)
1. Buy domain (e.g., `neptunenavigators.com`)
2. Add CNAME file with your domain
3. Configure DNS settings
4. Update `_config.yml` with new URL

## 🛠️ Local Development (Optional)

To preview locally before pushing:

```bash
# Install Jekyll
gem install bundler jekyll

# Create Gemfile
echo 'source "https://rubygems.org"' > Gemfile
echo 'gem "github-pages", group: :jekyll_plugins' >> Gemfile

# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# Open http://localhost:4000
```

## 📧 Contact

Email: neptunenavigators@gmail.com

---

**Built with assistance from [Clawdbot AI](https://clawd.bot)**
