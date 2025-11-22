# SYXY

A modern, interactive artist portfolio website featuring dynamic animations, video content, and a stunning visual gallery.

## 🎨 Overview

SYXY is a two-page web experience designed to showcase an artist's work with engaging animations and multimedia content. The site features an interactive particle animation landing page that transitions into a rich media portfolio.

## ✨ Features

### Landing Page (`index.html`)
- **Interactive Particle Animation**: Built with p5.js, featuring scrolling "Syxy" text particles
- **Mouse Interaction**: Particles scatter and react to mouse movements with physics-based animations
- **Responsive Design**: Adaptive layout that adjusts columns, font sizes, and particle counts based on screen size
- **Custom Typography**: Comforter Brush custom font with graceful fallbacks
- **Animated Play Button**: Eye-catching "bite" animation effect on click
- **Performance Optimized**: Mobile-friendly with reduced particle budgets and smart rendering

### Main Page (`play.html`)
- **Scrolling Ticker Header**: Smooth infinite scroll animation with the artist name
- **Video Hero Section**: Fullscreen autoplay video with gradient overlay
- **Social Media Integration**: Direct links to:
  - Instagram (@syxy)
  - TikTok (@syxxxxy)
  - Spotify
  - Apple Music
- **Image Gallery**: Stacked layout showcasing multiple high-quality images
- **Dark Theme**: Sleek, modern dark aesthetic
- **Fully Responsive**: Optimized for mobile, tablet, and desktop viewing

## 🚀 Quick Start

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/syxy.git
cd syxy
```

2. Serve the files using any local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js http-server
npx http-server -p 8000
```

3. Open your browser and navigate to:
```
http://localhost:8000
```

### Deployment

The site is pure HTML/CSS/JavaScript with no build step required. Simply upload all files to your web hosting service or deploy to:

- **GitHub Pages**
- **Netlify**
- **Vercel**
- **Cloudflare Pages**
- Any static hosting service

## 📁 Project Structure

```
syxy/
├── index.html              # Landing page with particle animation
├── play.html               # Main portfolio page
├── fonts/
│   ├── ComforterBrush-Regular.woff
│   └── HelveticaNeueCondensedBlack.woff
├── videos/
│   ├── syxy-hero.mp4
│   ├── syxy-hero-optimized.mp4
│   └── syxy-hero.webm
├── images/
│   ├── down-1.png
│   ├── down-2.png
│   ├── down-3.png
│   ├── down-4.png
│   ├── top-1.jpg
│   └── top-2.jpg
├── iCloud Photos from OP OP/
│   └── [3 PNG files]
├── iCloud Photos from OP OP 2/
│   └── [3 JPG files, 1 PNG]
└── Photoroom_20251118_232501.png  # Play button image
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern APIs
- **CSS3**: Custom properties, animations, responsive design
- **JavaScript**: Vanilla JS and p5.js for animations
- **p5.js v1.6.0**: Creative coding library for particle system
- **Custom Web Fonts**: WOFF format for optimal performance

## 🎯 Key Features Explained

### Particle System
The landing page uses a sophisticated particle system with:
- Multiple scrolling columns with alternating directions
- Physics-based particle behavior with velocity and damping
- Smooth return-to-home animation with easing
- Edge wrapping for infinite scroll effect
- Adaptive particle count based on device capabilities

### Responsive Behavior
- **Desktop**: Multiple columns, higher particle count, larger fonts
- **Tablet** (≤820px): Reduced columns, optimized spacing
- **Mobile** (≤480px): Single column, particle budget cap at 420, touch-optimized

### Performance Optimizations
- Pixel density limiting on mobile devices
- Particle budget system to prevent lag
- Lazy loading for images
- Optimized video formats (MP4/WebM)
- Font preloading and swap strategy

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari 14+
- iOS Safari 14+
- Chrome/Samsung Internet on Android

## 🎨 Customization

### Changing Colors
Edit the CSS custom properties in the `<style>` sections:
```css
background: #050505;  /* Main background */
color: #f8f8f8;       /* Text color */
```

### Adjusting Animations
Modify animation parameters in `index.html`:
```javascript
const scrollSpeed = 3.1;           // Particle scroll speed
const returnEase = 0.03;           // Return animation speed
const damping = 0.92;              // Velocity damping
```

### Social Links
Update the social media URLs in `play.html`:
```html
<a href="https://instagram.com/syxy" ...>
```

## 📝 License

Copyright © SYXY. All rights reserved.

## 🤝 Contributing

This is a personal portfolio project. If you find any bugs or have suggestions, feel free to open an issue.

## 📧 Contact

- Instagram: [@syxy](https://instagram.com/syxy)
- TikTok: [@syxxxxy](https://www.tiktok.com/@syxxxxy)
- Spotify: [SYXY](https://open.spotify.com/artist/5PaDQt5blNzLa0VtvpuTAL)
- Apple Music: [SYXY](https://music.apple.com/in/artist/syxy/1831920602)

---

Built with ❤️ using vanilla web technologies

