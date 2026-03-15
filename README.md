<div align="center">

# 🌐 Personal Portfolio

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**Modern, Responsive Portfolio Website Showcasing AI, Web & Android Development Projects**

[Features](#-features) • [Demo](#-demo) • [Projects](#-projects) • [Tech Stack](#-tech-stack) • [Setup](#-setup) • [Contributing](#-contributing)

---

</div>

## 🌟 Overview

A fully responsive, single-file personal portfolio website built with pure HTML, CSS, and vanilla JavaScript. Features smooth animations, interactive project galleries, multi-page SPA routing, and an elegant dark/light theme toggle.

### Why This Portfolio?

✨ **Single File Architecture**: Everything in one HTML file - no build tools required  
🎨 **Beautiful Design**: Modern UI with smooth animations and transitions  
📱 **Fully Responsive**: Perfect experience on desktop, tablet, and mobile  
🌓 **Theme Toggle**: Seamless dark/light mode switching  
⚡ **Fast Loading**: Optimized performance with minimal dependencies  
🎯 **Interactive**: Engaging project galleries with modal viewers

---

## ✨ Features

### 🎨 Modern Design System
- **Animated Hero Section**: Circular profile photo with orbiting gradient rings
- **Gradient Text Effects**: Shimmer animations on hero name
- **Smooth Transitions**: Page transitions with cubic-bezier easing
- **Floating Elements**: Animated info chips with floating effects

### 📱 Responsive Layout
- **Mobile-First Design**: Optimized for all screen sizes
- **Adaptive Navigation**: Hamburger menu for mobile devices
- **Flexible Grids**: Auto-adjusting project and skill cards
- **Touch-Friendly**: Large tap targets for mobile users

### 🎯 Interactive Components
- **Project Galleries**: Click to view full-screen screenshots
- **Certificate Viewer**: Embedded PDF viewer for certifications
- **Skill Cards**: Hover effects with gradient borders
- **Contact Links**: Direct email, WhatsApp, GitHub, and LinkedIn

### 🔄 SPA Navigation
- **Multi-Page Routing**: Smooth page transitions without reload
- **Browser History**: Back button navigates through portfolio pages
- **Deep Linking**: Direct links to specific projects
- **Scroll Management**: Auto-close menu on scroll

---

## 🎬 Demo

### Desktop View
![Desktop Screenshot](https://via.placeholder.com/800x450?text=Desktop+View)

### Mobile View
![Mobile Screenshot](https://via.placeholder.com/375x667?text=Mobile+View)

### Dark/Light Theme
![Theme Toggle](https://via.placeholder.com/800x450?text=Theme+Toggle)

---

## 🛠️ Tech Stack

### Frontend
| Technology | Purpose |
|------------|---------|
| HTML5 | Semantic markup structure |
| CSS3 | Modern styling with animations |
| Vanilla JavaScript | Interactive functionality |
| Google Fonts | Typography (Plus Jakarta Sans, Space Grotesk) |

### Design Features
- **CSS Grid & Flexbox**: Responsive layouts
- **CSS Animations**: Smooth transitions and effects
- **CSS Variables**: Theme switching support
- **Media Queries**: Mobile-responsive design

### Architecture
- **Single-Page Application**: Client-side routing
- **Component-Based**: Modular CSS classes
- **State Management**: JavaScript-based page system
- **Local Storage**: Theme preference persistence

---

## 📦 Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
- Optional: Local server for development

### Quick Start

1. **Clone the repository**
```bash
git clone https://github.com/Ijlal-Hussaini/My-Portfolio.git
cd My-Portfolio
```

2. **Open in browser**
```bash
# Simply open Portfolio.html in your browser
# Or use a local server:

# Python
python -m http.server 8000

# Node.js
npx serve

# VS Code Live Server
# Right-click Portfolio.html → Open with Live Server
```

3. **View your portfolio**
```
http://localhost:8000/Portfolio.html
```

---

## 🎨 Customization

### Update Personal Information

Edit the HTML file to customize:

```html
<!-- Hero Section -->
<div class="hero-name">
  <span class="n1">Hi, I'm</span>
  <span class="n2">Your Name</span>
</div>

<!-- Contact Information -->
<a href="mailto:your.email@example.com">
  your.email@example.com
</a>
```

### Change Theme Colors

Modify CSS variables in the `<style>` section:

```css
:root {
  --cyan: #00d4ff;      /* Primary accent color */
  --purple: #9b59f5;    /* Secondary accent */
  --green: #00d68f;     /* Success color */
  --gold: #f5c518;      /* Highlight color */
}
```

### Add New Projects

Follow the existing project card structure:

```html
<div class="pcard" onclick="sp('proj-yourproject')">
  <div class="pt">
    <span class="pe">🚀</span>
    <div class="ptitle">Your Project Name</div>
    <div class="pdesc">Project description...</div>
  </div>
  <div class="pb">
    <div class="pbadges">
      <span class="pbadge">Tech1</span>
      <span class="pbadge">Tech2</span>
    </div>
    <span class="parrow">View Details →</span>
  </div>
</div>
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Width | Target Devices |
|------------|-------|----------------|
| Desktop | > 1100px | Large screens |
| Tablet | 768px - 1100px | Tablets, small laptops |
| Mobile | < 768px | Phones, small tablets |
| Small Mobile | < 640px | Small phones |

---

## 🎯 Features Breakdown

### Navigation System
- Fixed header with blur backdrop
- Smooth scroll to sections
- Active link highlighting
- Mobile hamburger menu
- Auto-close on scroll

### Hero Section
- Animated gradient text
- Orbiting profile photo
- Floating info chips
- Counter animations
- CTA buttons

### Project Gallery
- Grid layout with hover effects
- Modal image viewer
- Keyboard navigation (ESC to close)
- Click outside to close
- Responsive image sizing

### Certificate Viewer
- Embedded PDF display
- Lightbox modal
- Download functionality
- Mobile-optimized viewing

---

## 🐛 Troubleshooting

### Images Not Loading
**Issue**: Images show broken icon  
**Solution**: 
- Ensure image paths are correct
- Check image files are in the same directory
- Use relative paths: `./image.jpg`

### Theme Not Persisting
**Issue**: Theme resets on page reload  
**Solution**:
- Check browser localStorage is enabled
- Clear browser cache
- Verify JavaScript is enabled

### Mobile Menu Not Closing
**Issue**: Hamburger menu stays open  
**Solution**:
- Check JavaScript console for errors
- Ensure `cm()` function is defined
- Verify scroll event listener is attached

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Ways to Contribute
- 🐛 Report bugs
- 💡 Suggest new features
- 📝 Improve documentation
- 🎨 Enhance design
- ⚡ Optimize performance

### Development Guidelines
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test on multiple devices
5. Submit a pull request

---

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2026 Ijlal Hussain

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Acknowledgments

- **Google Fonts** - Beautiful typography
- **Font Awesome** - Icon library
- **Inspiration** - Modern portfolio designs
- **Community** - Open source contributors

---

## 📧 Contact

**Ijlal Hussain**  
Software Engineer | AI Developer | MERN Stack Developer | Android Developer

- 📧 Email: [your.email@example.com](mailto:your.email@example.com)
- 💼 LinkedIn: [linkedin.com/in/ijlal-hussain](https://linkedin.com/in/ijlal-hussain)
- 🐱 GitHub: [github.com/Ijlal-Hussaini](https://github.com/Ijlal-Hussaini)
- 📱 WhatsApp: [+92-XXX-XXXXXXX](https://wa.me/92XXXXXXXXXX)

---

## 🗺️ Roadmap

- [ ] Add blog section
- [ ] Implement contact form with EmailJS
- [ ] Add project filtering by technology
- [ ] Create admin panel for content management
- [ ] Add analytics integration
- [ ] Implement PWA features
- [ ] Add multi-language support
- [ ] Create downloadable resume generator

---

## 📊 Stats

![GitHub repo size](https://img.shields.io/github/repo-size/Ijlal-Hussaini/My-Portfolio)
![GitHub stars](https://img.shields.io/github/stars/Ijlal-Hussaini/My-Portfolio?style=social)
![GitHub forks](https://img.shields.io/github/forks/Ijlal-Hussaini/My-Portfolio?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/Ijlal-Hussaini/My-Portfolio?style=social)

---

<div align="center">

**Made with ❤️ using HTML, CSS & JavaScript**

[⬆ Back to Top](#-personal-portfolio)

</div>
