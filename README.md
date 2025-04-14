# AI Tools Directory 🤖

> The ultimate directory of AI tools and resources for professionals, developers, and enthusiasts.

[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR-NETLIFY-ID/deploy-status)](https://app.netlify.com/sites/your-site/deploys)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Support & Resources](#support--resources)

## Overview

AI Tools is a comprehensive directory website showcasing artificial intelligence tools and resources in a clean, responsive 3-column grid layout. The site is built with HTML, CSS, and JavaScript, making it easy to customize and maintain.

## Features

- 🎯 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 💨 Fast loading times
- 📱 Mobile-friendly design
- 🎨 Customizable styling
- 🔄 Easy content updates

## Getting Started

### Prerequisites
- Git
- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-tools-directory.git
```

2. Navigate to project directory:
```bash
cd ai-tools-directory
```

3. Open `index.html` in your browser to view the site locally.

## Directory Structure

```
ai-tools-directory/
├── index.html
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── responsive.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── data/
│   └── directory-items.json
└── README.md
```

## Customization Guide

### Adding Directory Items

1. Open `data/directory-items.json`
2. Add new items following this format:

```json
{
  "name": "Tool Name",
  "description": "Tool description goes here",
  "category": "Category Name",
  "url": "https://toolurl.com",
  "image": "tool-image.jpg"
}
```

### Modifying Categories

1. Open `index.html`
2. Locate the category section:

```html
<div class="categories">
  <button class="category-btn active" data-category="all">All</button>
  <button class="category-btn" data-category="category1">Category 1</button>
  <!-- Add more categories here -->
</div>
```

### Updating Hero Section

1. Open `index.html`
2. Find the hero section:

```html
<section class="hero">
  <h1>AI Tools Directory</h1>
  <p>Your tagline here</p>
</section>
```

### Customizing Colors

1. Open `assets/css/style.css`
2. Modify the root variables:

```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --background-color: #ffffff;
  /* Add more custom colors */
}
```

## Deployment

### Netlify Deployment

1. Create a Netlify account
2. Connect your GitHub repository
3. Configure build settings:
   - Build command: `none`
   - Publish directory: `/`
4. Click "Deploy site"

## Custom Domain Setup

1. Purchase domain from preferred registrar
2. In Netlify:
   - Go to Site settings > Domain management
   - Click "Add custom domain"
   - Follow DNS configuration instructions

## Troubleshooting

### Common Issues

**Images not loading**
- Check image paths in `directory-items.json`
- Ensure images are in correct directory
- Verify file permissions

**Search not working**
- Check browser console for errors
- Verify `main.js` is properly linked
- Clear browser cache

## Support & Resources

- 📖 [Documentation Wiki](https://github.com/yourusername/ai-tools-directory/wiki)
- 🐛 [Issue Tracker](https://github.com/yourusername/ai-tools-directory/issues)
- 💬 [Community Forum](https://github.com/yourusername/ai-tools-directory/discussions)

### Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

- [Font Awesome](https://fontawesome.com) - Icons
- [Google Fonts](https://fonts.google.com) - Typography
- [Netlify](https://netlify.com) - Hosting

---

Made with ❤️ by [Your Name](https://github.com/yourusername)