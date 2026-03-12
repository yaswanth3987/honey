# 🍯 Honey - Premium Luxury Fashion Website

A modern, elegant luxury fashion e-commerce website built with React.js, featuring a soft luxury aesthetic with a dark matte background, blush pink, and champagne gold accents.

## ✨ Features

- **Mobile-First Responsive Design**: Optimized for all device sizes from mobile to desktop
- **Modern CSS with Styled Components**: No Bootstrap - pure, custom styling
- **Smooth Animations**: Powered by Framer Motion for elegant transitions
- **Glassmorphism Design**: Modern glass-effect cards with blur effects
- **Skeleton Loading**: Professional loading placeholders while content loads
- **Lazy Loading Images**: Performance-optimized image loading
- **Smooth Scroll Behavior**: Native smooth scrolling throughout
- **Page Transitions**: Beautiful animations between page changes
- **Reusable Components**: Clean, modular component architecture

## 🎨 Design System

### Color Palette
- **Dark Matte Background**: `#1a1a1a`
- **Blush Pink Accent**: `#c9a987`
- **Champagne Gold**: `#d4af37`
- **Text**: `#e8e8e8`
- **Muted Text**: `#b0b0b0`

### Typography
- **Headings**: Playfair Display (serif) - elegant, premium feel
- **Body**: Poppins (sans-serif) - clean, modern readability

### Responsive Breakpoints
- Mobile: `480px`
- Tablet: `768px`
- Desktop: `1024px`
- Wide: `1440px`

## 📁 Project Structure

```
honey-luxury-fashion/
├── src/
│   ├── components/
│   │   ├── Hero/
│   │   │   └── Hero.jsx                 # Hero banner component
│   │   ├── Navbar/
│   │   │   └── Navbar.jsx               # Navigation with smooth scroll
│   │   ├── Footer/
│   │   │   └── Footer.jsx               # Footer with links
│   │   ├── ProductCard/
│   │   │   └── ProductCard.jsx          # Reusable product card with animations
│   │   └── Skeleton/
│   │       └── Skeleton.jsx             # Loading placeholder component
│   ├── pages/
│   │   └── Home.jsx                     # Home page with featured products
│   ├── hooks/
│   │   └── useScrollAnimation.js        # Custom hook for scroll animations
│   ├── utils/
│   │   └── lazyLoading.js               # Lazy loading utilities
│   ├── styles/
│   │   ├── GlobalStyles.js              # Global styling with styled-components
│   │   └── theme.js                     # Design tokens and theme configuration
│   ├── App.jsx                          # Main app component with routing
│   └── main.jsx                         # React entry point
├── index.html                           # HTML template
├── vite.config.js                       # Vite configuration
├── package.json                         # Dependencies and scripts
└── README.md                            # This file
```

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ and npm 8+

### Installation

1. **Install dependencies**
```bash
npm install
```

2. **Start development server**
```bash
npm run dev
```
The application will open at `http://localhost:5173`

3. **Build for production**
```bash
npm run build
```

4. **Preview production build**
```bash
npm run preview
```

## 📦 Dependencies

- **React** - UI library
- **React DOM** - DOM rendering
- **Styled Components** - CSS-in-JS styling
- **Framer Motion** - Animation library
- **Vite** - Build tool and dev server

## 🎯 Component Overview

### 🎨 Hero Component
- Full-screen hero banner with gradient background
- Animated title and description
- Call-to-action buttons with hover effects
- Floating background elements
- Responsive image display

### 🛍️ ProductCard Component
- Glassmorphism design with blur effect
- Skeleton loading state
- Lazy-loaded images
- Favorite/wishlist toggle
- Product badges (New, Sale, etc.)
- Smooth hover animations
- Responsive grid layout

### 🔝 Navbar Component
- Fixed, glassmorphic navigation
- Smooth scroll detection
- Icon buttons (search, favorites, cart)
- Dynamic background on scroll
- Mobile-responsive menu

### 🏁 Footer Component
- Multi-column layout
- Link sections
- Social media links
- Copyright information
- Responsive grid

## 🎬 Animation Features

- **Page transitions** with stagger effects
- **Hover animations** on buttons and cards
- **Scroll-triggered animations** using Intersection Observer
- **Floating background elements** with CSS animations
- **Glassmorphism effects** with CSS blur and transparency
- **Image loading animations** with fade-in effects
- **Skeleton loading** with gradient shimmer animation

## 📱 Responsive Design

All components are built with a mobile-first approach:
- Flexible grid layouts using CSS Grid
- Responsive typography with `clamp()` function
- Touch-friendly button sizes (44px minimum)
- Optimized spacing for different screen sizes
- Hidden/shown elements based on viewport

## ♿ Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Smooth scroll behavior
- High contrast text colors
- Keyboard-navigable interactive elements

## 🎓 Key Learnings

This project demonstrates:
- Functional components and hooks in React
- Styled Components for modern CSS-in-JS
- Framer Motion for complex animations
- Responsive design principles
- Component composition and reusability
- Performance optimization (lazy loading)
- Design system implementation

## 📝 License

This project is provided as a template for educational purposes.

---

Made with ❤️ for a luxurious user experience
