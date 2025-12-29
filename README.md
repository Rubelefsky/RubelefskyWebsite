<div align="center">

# 🌐 Rubelefsky Portfolio Website

### Professional IT Support & Cybersecurity Portfolio

[![Live Demo](https://img.shields.io/badge/🌐-Live%20Demo-blue?style=for-the-badge)](https://rubelefsky.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/brandonsrubell/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/Rubelefsky)

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Google_Analytics-E37400?style=flat&logo=google-analytics&logoColor=white" alt="Google Analytics" />

---

</div>

## ✨ Overview

A modern, high-performance portfolio website showcasing Brandon Rubell's journey from IT Support Engineer to Cybersecurity Professional. Built entirely with vanilla web technologies, featuring sophisticated animations, interactive visual effects, and enterprise-grade security practices. The site demonstrates technical proficiency through custom-built animations, performance optimization, and accessibility-first design.

## 🚀 Features

<table>
<tr>
<td width="50%">

### 🎨 Design & Visual Effects
- **Animated Background System** - Dual-layer gradient blur with floating animations
- **Interactive Cursor Glow** - Desktop-only smooth-following radial gradient (30% opacity)
- **Grid Overlay** - Subtle 50px grid with 3% opacity for depth
- **Glassmorphism UI** - Backdrop-filter blur effects on navigation and cards
- **Custom Gradient Palette** - Indigo-purple-cyan gradient system
- **Smooth Page Transitions** - Cubic-bezier easing for professional feel
- **Card Hover Effects** - translateY animations with dynamic shadows

</td>
<td width="50%">

### ⚡ Performance & Technical
- **Zero Dependencies** - 100% vanilla JavaScript
- **Intersection Observer API** - Efficient scroll-based animations
- **Staggered Animations** - Sequential reveals with custom delays
- **Parallax Effects** - Subtle hero section parallax on scroll
- **Responsive Typography** - Clamp-based fluid font sizing
- **Content Security Policy** - CSP headers for XSS protection
- **SEO Optimized** - Semantic HTML5, Open Graph, Twitter Cards
- **Google Analytics** - GA4 tracking integration

</td>
</tr>
</table>

## 📂 Project Structure

```
Website/
├── RubelefskyWebsite/
│   └── RubelefskyWebsite/
│       ├── mainpage/
│       │   ├── index.html          # Main portfolio page
│       │   ├── styles.css          # Custom styling & animations
│       │   ├── script.js           # Interactive features
│       │   ├── favicon.png         # Site icon
│       │   └── robots.txt          # SEO configuration
│       └── README.md               # Project documentation
├── RubelefskyAzureCloudResume/     # Azure-hosted resume
└── README.md                       # This file
```

## 🛠️ Technologies & Implementation

| Technology | Purpose | Implementation Details |
|------------|---------|------------------------|
| **HTML5** | Semantic markup | Accessible structure, meta tags for SEO/social sharing |
| **CSS3** | Advanced styling | CSS Grid, Flexbox, custom properties, animations, backdrop-filter |
| **Vanilla JavaScript** | Interactivity | Event delegation, Intersection Observer, requestAnimationFrame |
| **Google Analytics** | Analytics | GA4 tracking (ID: G-2RH3QV9D7V) |
| **Inter Font** | Typography | Google Fonts with display=swap optimization |
| **CSP** | Security | Content Security Policy headers to prevent XSS attacks |

## 📱 Page Sections

### 🏠 Hero Section
- **Dynamic Badge** - "Open to Opportunities" with blinking green indicator
- **Gradient Title** - Large-scale responsive heading with gradient text effect
- **Dual CTAs** - Email contact and Azure-hosted resume link
- **Animated Entry** - Staggered fadeInUp animations (0.1s - 0.8s delays)
- **Pulsing Background** - 8s infinite pulse animation with radial gradient

### 👤 About Section
- **Two-Column Layout** - Narrative text with skill grid
- **4 Skill Cards** - IT Support, Security, Cloud, Troubleshooting
- **Hover Interactions** - -8px translateY with shadow enhancement
- **Gradient Top Border** - Scales from 0 to 100% on hover
- **Responsive Grid** - Collapses to single column on mobile

### 💼 Experience Timeline
- **Vertical Timeline** - Centered line with gradient (indigo to cyan)
- **3 Timeline Items** - Current role, transition phase, future goals
- **Glowing Dots** - 16px circles with box-shadow glow effects
- **Alternating Layout** - Odd items on right, even on left
- **Mobile Optimization** - Left-aligned timeline for small screens

### 📞 Contact Section
- **3 Contact Links** - LinkedIn, GitHub, Email
- **Hover Effects** - -4px lift with glow shadow
- **Icon Integration** - Inline SVG icons with 20px sizing
- **Responsive Stack** - Vertical layout on mobile devices

## 🎯 Key Technical Highlights

- ⚡ **Zero Dependencies** - Pure HTML/CSS/JS, no frameworks or libraries
- 🎨 **Advanced CSS Techniques** - Custom properties, CSS Grid, Flexbox, backdrop-filter, clamp()
- 📱 **Mobile-First Responsive** - Breakpoint at 768px with comprehensive media queries
- 🔒 **Security Hardened** - CSP headers, input validation, secure external resource loading
- 🚀 **Performance Optimized** - Lazy loading via Intersection Observer, requestAnimationFrame for smooth animations
- ♿ **Accessibility Ready** - Semantic HTML5, proper heading hierarchy, ARIA-compatible structure
- 🎭 **Sophisticated Animations** - Keyframe animations, cubic-bezier easing, staggered delays
- 🖱️ **Desktop Enhancements** - Pointer media query for cursor glow (fine pointer devices only)

## 🌐 Live Deployment

**Production URL**: [https://rubelefsky.com](https://rubelefsky.com)

**Resume Subdomain**: [https://www.rubelefskyazurecloud.net/](https://www.rubelefskyazurecloud.net/)

The site features:
- SSL/TLS encryption
- SEO optimization with canonical URLs
- Open Graph and Twitter Card meta tags
- Google Analytics tracking (G-2RH3QV9D7V)
- robots.txt for search engine crawling

## 📝 Advanced Implementation Details

<details>
<summary><b>🎨 Visual Effects Architecture</b></summary>

**Background System (3 layers)**
- `.bg-gradient-blur::before` - Top-left radial gradient with 20s float animation
- `.bg-gradient-blur::after` - Bottom-right radial gradient with 25s reverse animation
- `.bg-grid` - Fixed 50px grid overlay at 3% opacity

**Cursor Glow System**
- Desktop detection via `matchMedia('(pointer: fine)')`
- Smooth follow using requestAnimationFrame with 0.1 easing
- 400px radial gradient with 30% opacity
- Hide/show on mouseleave/mouseenter events

**Animation Keyframes**
- `floatBlur` - 4-point bezier path for background movement
- `pulse` - Hero section 8s scale and opacity cycle
- `blink` - Status badge 2s opacity pulse
- `fadeInUp` - 30px translateY with opacity transition

</details>

<details>
<summary><b>⚡ JavaScript Architecture</b></summary>

**Scroll Management**
- Header scroll detection at 50px threshold
- Parallax effect with 0.3x scroll multiplier and opacity fade
- Smooth scrolling via native CSS `scroll-behavior: smooth`

**Intersection Observer Setup**
- Threshold: 0.1 (10% visibility)
- Root margin: `0px 0px -50px 0px` (trigger 50px early)
- Staggered delays: 0.1s for skills, 0.15s for timeline items
- One-time trigger with persistent `.active` class

**Interactive Effects**
- Mouse position tracking for card hover effects
- Event delegation for performance
- requestAnimationFrame for smooth 60fps animations

</details>

<details>
<summary><b>📱 Responsive System</b></summary>

**Breakpoint Strategy**
- Single breakpoint at 768px for mobile
- Mobile: Hidden navigation (hamburger recommended for future)
- Fluid typography using `clamp(min, preferred, max)`
  - H1: `clamp(2.5rem, 8vw, 4.5rem)`
  - Subtitle: `clamp(1.1rem, 3vw, 1.4rem)`

**Layout Adaptations**
- About: 2-column → 1-column stack
- Skills: 2×2 grid → single column
- Timeline: Centered → left-aligned with 60px offset
- Buttons: Inline → stacked at 280px max-width

</details>

<details>
<summary><b>🔒 Security Implementation</b></summary>

**Content Security Policy**
```
default-src 'self'
script-src 'self' https://www.googletagmanager.com 'unsafe-inline'
style-src 'self' 'unsafe-inline' https://fonts.googleapis.com
font-src 'self' https://fonts.gstatic.com
```

**Security Measures**
- Restricted script execution to trusted domains
- Font loading limited to Google Fonts
- External resource validation
- No inline JavaScript (except GA tracking)
- HTTPS-only external resources

</details>

## 🔧 Local Development

To run this website locally:

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Website/RubelefskyWebsite/RubelefskyWebsite/mainpage
   ```

2. **Open in browser**
   ```bash
   # Using Python's built-in server
   python3 -m http.server 8000

   # Or simply open the file
   open index.html
   ```

3. **View the site**
   - Navigate to `http://localhost:8000` if using a server
   - Or directly open `index.html` in your preferred browser

## 🎨 Design System

### Color Palette (CSS Custom Properties)

| Variable | Hex Code | Usage |
|----------|----------|-------|
| `--primary-color` | `#6366f1` | Primary brand color (Indigo) |
| `--primary-glow` | `rgba(99, 102, 241, 0.4)` | Glow effects and shadows |
| `--secondary-color` | `#8b5cf6` | Secondary accent (Purple) |
| `--accent-color` | `#06b6d4` | Tertiary accent (Cyan) |
| `--accent-glow` | `rgba(6, 182, 212, 0.4)` | Cyan glow effects |
| `--text-primary` | `#f1f5f9` | Main text color |
| `--text-secondary` | `#94a3b8` | Subheadings and descriptions |
| `--text-muted` | `#64748b` | Tertiary text |
| `--bg-primary` | `#0a0a0f` | Main background (near-black) |
| `--bg-secondary` | `#111118` | Section backgrounds |
| `--bg-card` | `rgba(17, 17, 24, 0.8)` | Card backgrounds with transparency |
| `--bg-card-hover` | `rgba(30, 30, 45, 0.9)` | Card hover states |
| `--border-subtle` | `rgba(99, 102, 241, 0.2)` | Default borders |
| `--border-glow` | `rgba(99, 102, 241, 0.5)` | Hover state borders |

### Gradients
- **Primary Gradient**: `135deg, #6366f1 → #8b5cf6 → #06b6d4`
- **Text Gradient**: `135deg, #6366f1 → #a855f7 → #06b6d4`

### Typography
- **Font Family**: Inter (Google Fonts) with system fallbacks
- **Font Weights**: 300, 400, 500, 600, 700, 800
- **Line Height**: 1.6 (body), varies by element

## 📊 File Structure & Metrics

```
mainpage/
├── index.html          # 220 lines - Semantic HTML5 structure
├── styles.css          # 765 lines - Advanced CSS with animations
├── script.js           # 141 lines - Vanilla JavaScript interactions
├── favicon.png         # 911 KB - Site favicon
├── og-image.jpg        # 771 KB - Social media preview image
└── robots.txt          # 24 bytes - Search engine directives
```

**Total Size**: ~1.7 MB (optimizable with image compression)

## 🎓 Learning Outcomes Demonstrated

This project showcases proficiency in:
- ✅ Vanilla JavaScript (ES6+) - No jQuery or framework dependencies
- ✅ Modern CSS architecture with custom properties
- ✅ Performance optimization techniques
- ✅ Web security best practices (CSP, XSS prevention)
- ✅ Responsive design patterns
- ✅ Intersection Observer API for efficient scroll animations
- ✅ requestAnimationFrame for smooth 60fps animations
- ✅ SEO optimization with semantic HTML and meta tags
- ✅ Accessibility-first development approach

## 🚀 Future Enhancements

Potential improvements identified:
- [ ] Mobile hamburger navigation menu
- [ ] Image optimization (WebP format, compression)
- [ ] Dark/light mode toggle
- [ ] Blog integration for technical articles
- [ ] Contact form with backend integration
- [ ] PWA capabilities (service worker, offline support)
- [ ] Performance monitoring integration
- [ ] A/B testing for CTA optimization

## 🤝 Connect

<div align="center">

**Brandon Rubell** - IT Support & Cybersecurity Professional

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brandonsrubell/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rubelefsky)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@rubelefsky.com)

</div>

---

<div align="center">

**Built with Vanilla Web Technologies**

*Showcasing the transition from IT Support to Cybersecurity*

![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-green?style=flat)
![Pure Vanilla](https://img.shields.io/badge/Framework-None-blue?style=flat)
![File Size](https://img.shields.io/badge/Total%20Size-~1.7MB-orange?style=flat)

**© 2026 Brandon Rubell (Rubelefsky). All rights reserved.**

</div>
