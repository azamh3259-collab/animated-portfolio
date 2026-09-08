# Animated Creative Portfolio 🎨

A modern, minimalist animated portfolio website with smooth interactions, stunning visual effects, and responsive design. Perfect for showcasing creative work and building a strong online presence.

## ✨ Features

- **Smooth Animations** - Scroll-triggered animations and transitions throughout the site
- **Modern Design** - Minimalist aesthetic with gradient accents and ambient backgrounds
- **Responsive Layout** - Fully responsive design that works on all devices
- **Interactive Elements** - Hover effects, parallax scrolling, and smooth navigation
- **Performance Optimized** - Clean code and efficient animations
- **SEO Friendly** - Proper semantic HTML structure
- **Accessibility** - Semantic markup and keyboard-friendly navigation

## 🎯 Sections

1. **Navigation Bar** - Fixed header with smooth blur effect and active state detection
2. **Hero Section** - Eye-catching landing with animated text reveals
3. **Portfolio Grid** - Showcase your work with animated project cards
4. **About Section** - Tell your story with content and visual elements
5. **Contact Footer** - Call-to-action and social links

## 🚀 Getting Started

### Option 1: View Online
Open `index.html` directly in your web browser to see the portfolio in action.

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/azamh3259-collab/animated-portfolio.git
cd animated-portfolio

# Open with a local server (recommended)
# Using Python 3:
python -m http.server 8000

# Using Node.js (if you have http-server installed):
npx http-server

# Then open: http://localhost:8000
```

## 🛠️ Customization

### Edit Portfolio Cards
In `index.html`, find the `.grid` section and modify the `.card` elements:

```html
<div class="card">
    <div class="card-image-wrapper">
        <div class="card-graphic" style="border-radius: 30% 70% 70% 30% / 30% 30% 70% 70%;"></div>
    </div>
    <div class="card-info">
        <div class="card-category">Your Category</div>
        <div class="card-title">Your Project Title</div>
        <div class="card-desc">Your project description here.</div>
    </div>
</div>
```

### Change Colors
Update the CSS variables in the `:root` section:

```css
:root {
    --bg-color: #0a0a12;
    --text-color: #ffffff;
    --accent-color: #7000ff;
    --accent-glow: #00f0ff;
}
```

### Modify Brand Name
Replace "CREATIVE.IO" in the logo section with your name or brand:

```html
<div class="logo">YOUR BRAND</div>
```

## 🎨 Animation Details

### Scroll Animations
Cards fade in and slide up as they come into view using Intersection Observer API.

### Parallax Effect
Background glow moves subtly with scroll for depth perception.

### Hover Effects
- Cards lift and scale on hover
- Border glow appears on interaction
- Graphics rotate and scale inside cards

### Navigation
- Navigation bar background strengthens on scroll
- Smooth scrolling between sections
- Active link detection

## 📱 Responsive Breakpoints

- **Desktop**: Full featured experience with 3-column grid
- **Tablet**: 2-column grid layout
- **Mobile**: Single column with optimized spacing

## 🔧 Technology Stack

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with animations and gradients
- **JavaScript (Vanilla)** - No dependencies required
- **Intersection Observer API** - For scroll animations

## 📦 File Structure

```
animated-portfolio/
├── index.html          # Main HTML file with all content and styles
└── README.md           # This file
```

## 🌐 Deployment

### Deploy to GitHub Pages
1. Go to repository Settings → Pages
2. Select "Deploy from a branch"
3. Choose `main` branch and `root` folder
4. Your site will be live at: `https://azamh3259-collab.github.io/animated-portfolio/`

### Deploy to Netlify
1. Connect your GitHub repository
2. Build command: (leave empty)
3. Publish directory: (leave empty or set to root)
4. Deploy

### Deploy to Vercel
1. Import the repository from GitHub
2. Vercel will automatically detect it's a static site
3. Click Deploy

## 🎬 Adding Real Images

Replace the abstract graphics with real images:

```html
<div class="card-image-wrapper">
    <img src="your-image.jpg" alt="Project name" style="width: 100%; height: 100%; object-fit: cover;">
</div>
```

## ✅ Performance Tips

- Optimize images before adding them
- Use WebP format for better compression
- Lazy load images for faster initial load
- Minimize CSS and JavaScript in production

## 📝 License

This project is free to use and modify for personal and commercial purposes.

## 🤝 Support

For questions or issues, feel free to open an issue on GitHub.

---

**Made with ❤️ by Creative Studio**
