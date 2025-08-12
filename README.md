<div align="center">

![YasMade Logo](./public/logo-light.png#gh-light-mode-only)
![YasMade Logo](./public/logo-dark.png#gh-dark-mode-only)

# 🌸 YasMade - Handcrafted Embroidery & Creative Workshops

**A modern e-commerce platform for artisanal embroidery, creative workshops, and Islamic-inspired art**

[![React](https://img.shields.io/badge/React-18.2.0-blue.svg)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.4.2-green.svg)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.3.5-06B6D4.svg)](https://tailwindcss.com/)
[![Supabase](https://img.shields.io/badge/Supabase-Database-3ECF8E.svg)](https://supabase.com/)

</div>

## ✨ Overview

YasMade is a beautifully crafted, full-stack e-commerce platform that seamlessly blends traditional Islamic art with modern web technology. This project showcases the intersection of faith, creativity, and technology through handcrafted embroidery products, educational workshops, and a vibrant community experience.

### 🎯 Key Features

- **🛍️ Complete E-commerce Experience** - Product catalog, shopping cart, and secure checkout
- **📚 Rich Content Management** - Blog posts, workshop sessions, and educational content
- **🎨 Islamic Art & Design** - Beautiful, culturally-inspired design system
- **🌙 Dark/Light Mode** - Seamless theme switching with Islamic color palettes
- **📱 Fully Responsive** - Optimized for all devices from mobile to desktop
- **🔐 Secure Authentication** - Admin dashboard with role-based access
- **📧 Email Integration** - Contact forms, newsletters, and order confirmations

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Supabase account

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/yasmade-demo.git
cd yasmade-demo

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local

# Start the development server
npm run dev
```

### Environment Variables

Create a `.env.local` file with:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 🏗️ Architecture

### Tech Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| **Frontend** | React 18 + Vite | Fast, modern UI framework |
| **Styling** | Tailwind CSS + Custom Design System | Responsive, beautiful design |
| **State Management** | Zustand | Lightweight state management |
| **Backend** | Supabase | Database, authentication, storage |
| **Email** | EmailJS + Resend | Transactional emails |
| **Deployment** | Netlify/Vercel ready | Easy deployment |

### Project Structure

```
yasmade-demo/
├── src/
│   ├── components/          # Reusable UI components
│   │   ├── common/         # Shared components
│   │   ├── layout/         # Header, Footer, Layout
│   │   └── home/          # Homepage specific components
│   ├── pages/             # Route-based page components
│   ├── contexts/          # React contexts (Theme, Supabase)
│   ├── hooks/            # Custom React hooks
│   ├── stores/           # Zustand state stores
│   ├── utils/            # Utility functions
│   └── constants/        # App constants
├── supabase/
│   ├── functions/        # Edge functions
│   └── migrations/       # Database migrations
└── public/              # Static assets
```

## 🎨 Design System

### Color Palette

The design system draws inspiration from Islamic art and nature:

- **Primary**: Violet to Fuchsia gradient (spirituality & creativity)
- **Secondary**: Soft purples and pinks (warmth & femininity)
- **Neutrals**: Warm grays and whites (elegance & simplicity)

### Typography

- **Primary Font**: Nunito (friendly, approachable)
- **Headings**: Bold, with gradient text effects
- **Body**: Clean, readable with excellent hierarchy

### Components

- **Cards**: Soft shadows with hover animations
- **Buttons**: Gradient backgrounds with smooth transitions
- **Forms**: Clean, accessible with real-time validation
- **Images**: Lazy loading with shimmer effects

## 📊 Features Deep Dive

### 🛍️ E-commerce

- **Product Catalog** with filtering and search
- **Shopping Cart** with persistent storage
- **Secure Checkout** with Stripe integration
- **Order Management** for customers and admins
- **Inventory Tracking** with low stock alerts

### 📚 Content Management

- **Rich Text Editor** for blog posts and product descriptions
- **Image Optimization** with automatic resizing
- **SEO Optimization** with meta tags and structured data
- **Social Sharing** with Open Graph integration

### 🎓 Workshops

- **Session Scheduling** with calendar integration
- **Registration System** with capacity management
- **Payment Processing** for paid workshops
- **Email Reminders** and confirmations

### 🔐 Admin Dashboard

- **Comprehensive Analytics** with real-time data
- **Content Management** for products, blogs, and sessions
- **Order Management** with status tracking
- **Customer Communication** tools
- **Settings Management** for site configuration

## 🌐 Performance & SEO

### Performance Optimizations

- **Code Splitting** with React.lazy() and Suspense
- **Image Optimization** with lazy loading and WebP
- **Bundle Optimization** with Vite's tree shaking
- **Caching Strategy** with service worker ready
- **CDN Integration** for static assets

### SEO Features

- **Meta Tags** for all pages
- **Open Graph** tags for social sharing
- **Structured Data** with JSON-LD
- **Sitemap Generation** ready
- **Robots.txt** configured

## 🚀 Deployment

### One-Click Deployments

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/yasmade-demo)
[![Deploy with Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yourusername/yasmade-demo)

### Manual Deployment

```bash
# Build for production
npm run build

# Preview production build
npm run preview

# Deploy to your preferred platform
# Upload the dist/ folder to your hosting provider
```

## 🔧 Development

### Available Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint         # Run ESLint
```

### Code Style

- **ESLint** configured with React hooks rules
- **Prettier** for consistent formatting
- **Conventional Commits** for git messages
- **TypeScript** ready (easily convertible)

## 🧪 Testing

```bash
# Run tests (when implemented)
npm test

# Run tests in watch mode
npm run test:watch
```

## 📈 Analytics & Monitoring

- **Google Analytics** integration ready
- **Performance Monitoring** with Web Vitals
- **Error Tracking** with Sentry integration ready
- **User Analytics** with privacy-focused solutions

<!-- ## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details. -->

<!-- 1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request -->

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Islamic Art & Design** - For inspiring the beautiful aesthetics
- **Tailwind CSS** - For the amazing utility-first framework
- **Supabase** - For the incredible backend-as-a-service
- **The React Community** - For continuous innovation and support

<!-- ## 📞 Support

For support, email [info@yasmade.com](mailto:info@yasmade.com) or join our [Discord community](https://discord.gg/yasmade). -->

---

<div align="center">

**Made with ❤️ by the elprince-dev**

<!-- [Website](https://yasmade.com) • [Instagram](https://instagram.com/yasmade) • [Facebook](https://facebook.com/yasmade) -->

</div>
