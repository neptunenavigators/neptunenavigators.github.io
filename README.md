# Neptune Navigators Website v2

Official website for Neptune Navigators with interactive demos.

## 🎬 Features

- Side-by-side AI detection video comparison
- Interactive 3D port model viewer (rotate, zoom, explore)
- Responsive design
- Optimized for GitHub Pages

## 📂 File Structure

```
neptunenavigators-site-v2/
├── _config.yml
├── index.html
├── _layouts/
│   └── default.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── videos/
│   │   ├── mix_540p_h264.mp4
│   │   └── mix_render_540p_h264.mp4
│   └── models/
│       └── port.glb
├── Gemfile
└── README.md
```

## 🚀 Deployment

### 1. Create Asset Directories
```bash
mkdir -p assets/videos assets/models
```

### 2. Copy Media Files
```bash
cp /home/pawel/neptunenavigators-site/mix_540p_h264.mp4 assets/videos/
cp /home/pawel/neptunenavigators-site/mix_render_540p_h264.mp4 assets/videos/
cp /home/pawel/neptunenavigators-site/port.glb assets/models/
```

### 3. Push to GitHub
```bash
git init
git add .
git commit -m "Add interactive demos: videos + 3D model"
git branch -M main
git remote add origin git@github.com:neptunenavigators/neptunenavigators.github.io.git
git push -u origin main
```

### 4. GitHub Pages will deploy automatically
Visit: https://neptunenavigators.github.io

## 🎮 3D Model Controls

- **Rotate:** Click and drag
- **Zoom:** Scroll wheel
- **Pan:** Right-click and drag
- **Auto-rotate:** Enabled by default

## 🔧 Local Preview

```bash
bundle install
bundle exec jekyll serve
# Visit http://localhost:4000
```

---

**Built with assistance from [Clawdbot AI](https://clawd.bot)**
