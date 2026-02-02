# Tools and Technical Stack Overview

This document outlines the tools, technologies, and standards used in the Neptune Navigators website.

## 💻 Tech Stack
- **Framework**: [Jekyll](https://jekyllrb.com/) (Ruby-based static site generator).
- **Structure**: Semantic HTML5.
- **Styling**: Vanilla CSS (no external frameworks like Tailwind unless specified).
- **Layouts**: Custom layouts in `_layouts/` (e.g., `default.html`).

## 🎥 Media & Interactivity
- **Videos**: High-quality MP4/H.264 files located in `assets/videos/`.
- **3D Models**: GLB/GLTF models in `assets/models/`.
- **3D Viewer**: Google's [`<model-viewer>`](https://modelviewer.dev/) for cross-browser, AR-ready 3D rendering.
- **3D Engine**: Three.js (used under-the-hood by model-viewer).

## 🚀 Development & Deployment
- **Package Management**: Bundler (`Gemfile`).
- **Local Preview**: `bundle exec jekyll serve`.
- **Hosting**: GitHub Pages (automated deployment from the `main` branch).
- **Asset Directory**: Always use the `/assets/` directory for styles, models, and videos.

## 📏 Engineering Standards
- **SEO**: descriptive title tags, meta descriptions, and proper H1 hierarchy.
- **Performance**: Lazy loading for videos and large 3D models.
- **Responsiveness**: Mobile-first design approach.
- **Clean Code**: Commented CSS blocks and clean, semantic HTML sections.
