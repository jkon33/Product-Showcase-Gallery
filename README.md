# Product Showcase Gallery 🌓

A responsive, interactive product gallery with light/dark mode toggle and smooth animations. Built with pure HTML, CSS, and JavaScript – no frameworks or dependencies.

![Product Gallery Demo](http://btc2eth.me/Product-Showcase-Gallery)

## ✨ Features

- **3‑Card Product Grid** – Responsive layout that adapts to any screen size
- **Light/Dark Theme Toggle** – Smooth theme switching with persistent preference (saved to localStorage)
- **Smooth Animations** – Fade-in on load, staggered card appearance, hover effects
- **Glassmorphism Design** – Frosted glass cards with backdrop blur
- **Hover Interactions** – Cards lift, shadows deepen, and buttons change color
- **Theme Persistence** – Remembers user's last choice across sessions
- **Fully Responsive** – Works perfectly on mobile, tablet, and desktop

## 🚀 Quick Start

1. **Clone or download** this repository
2. Open `index.html` in any modern web browser
3. Click the sun/moon icons to toggle between light and dark themes

That's it! No build steps, no installation, no configuration.

## 🎨 Customization

### Adding Your Own Products

Edit the HTML section inside `.card-grid`:

```html
<div class="product-card">
  <div class="card-image">🎧</div>  <!-- Change emoji or background -->
  <h2 class="product-title">Your Product</h2>
  <p class="product-description">Your description here</p>
  <div class="price-row">
    <span class="price">$99</span>
    <span class="buy-btn">shop →</span>
  </div>
</div>
