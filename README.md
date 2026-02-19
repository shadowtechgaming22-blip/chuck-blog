# Chuck's Blog ✦

A premium dark-themed blog built with inspiration from the StoryHub design aesthetic. Features bold typography, vibrant magenta accents, overlapping card layouts, and an editorial magazine feel.

![Design Preview](./preview.png)

## ✨ Features

- **Premium Dark Theme** — Deep blacks with vibrant magenta/pink accent colors
- **Bold Typography** — Space Grotesk headings with Inter body text
- **Overlapping Cards** — Layered design elements creating visual depth
- **Editorial Layout** — Magazine-style asymmetric grids and spacing
- **Smooth Animations** — Ambient background blobs, hover effects, and scroll transitions
- **Responsive Design** — Optimized for all device sizes
- **CSS-Generated Visuals** — No external image dependencies, everything is code

## 🎨 Design System

### Colors
- **Primary Background:** `#0a0a0b`
- **Secondary Background:** `#111114`
- **Card Background:** `rgba(26, 26, 31, 0.8)`
- **Accent Magenta:** `#e91e8c`
- **Accent Pink:** `#f472b6`
- **Accent Purple:** `#a855f7`

### Typography
- **Headings:** Space Grotesk (700 weight)
- **Body:** Inter (300-600 weights)

### Visual Effects
- Ambient animated gradient blobs
- Subtle noise texture overlay
- Grid pattern with radial mask
- Glassmorphism cards with backdrop blur

## 📁 Structure

```
chuck-blog/
├── index.html              # Main landing page
├── articles/
│   └── best-email-marketing-2025.html
├── images/                 # Generated hero images (optional)
└── README.md
```

## 🚀 Getting Started

1. Clone the repository
2. Open `index.html` in your browser
3. No build step required — pure HTML/CSS

## 📝 Adding Articles

1. Create a new HTML file in the `articles/` directory
2. Copy the structure from an existing article
3. Update the content, title, and meta information
4. Add a card to the main `index.html` grid

## 🎯 Inspiration

This design draws inspiration from:
- **StoryHub Gatsby Template** — Editorial layout and card aesthetics
- **Modern Dark Mode Trends** — High contrast with vibrant accents
- **Magazine Design** — Asymmetric grids and generous whitespace

## 🔧 Customization

### Changing Colors
Edit the CSS variables in `:root`:
```css
--accent-magenta: #e91e8c;
--accent-pink: #f472b6;
```

### Adding Hero Images
Replace the CSS-generated backgrounds with actual images:
```html
<div class="featured-image">
    <img src="images/your-image.png" alt="Description">
</div>
```

## 📄 License

MIT License — feel free to use this design for your own projects!

---

Built with ❤️ by Chuck
