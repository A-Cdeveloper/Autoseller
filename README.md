# 🚗 Autoseller - Premium Vehicle Dealership

A modern, responsive web application for a premium vehicle dealership built with Next.js 15, featuring an extensive vehicle inventory, filtering system, and comprehensive accessibility support.

## ✨ Features

### 🚙 **Vehicle Management**

- **Complete Vehicle Inventory** - Browse extensive collection of cars, SUVs, and luxury vehicles
- **Advanced Filtering System** - Filter by brand, model, year, price range, and more
- **Detailed Vehicle Pages** - Comprehensive vehicle information with high-quality image galleries
- **Image Lightbox** - Full-screen image viewing with navigation controls
- **Equipment Details** - Detailed vehicle specifications and equipment lists

### 🏢 **Company Information**

- **About Us** - Company history and mission
- **Our Services** - Automotive maintenance, repairs, and professional car care
- **Contact Form** - Integrated contact form with email functionality
- **Interactive Map** - Google Maps integration for location
- **Partner Showcase** - Featured automotive partners and brands

### ♿ **Accessibility & Performance**

- **WCAG 2.1 Compliant** - Full ARIA support for screen readers
- **Keyboard Navigation** - Complete keyboard accessibility
- **Responsive Design** - Mobile-first approach with seamless desktop experience
- **Performance Optimized** - Dynamic imports, image optimization, and CSS minification
- **SEO Ready** - Meta tags, structured data, and semantic HTML

## 🛠️ Tech Stack

### **Frontend**

- **Next.js 15.4.6** with App Router and Turbopack
- **React 19.1.0** with TypeScript
- **Tailwind CSS** for styling with PostCSS optimization
- **Framer Motion** for animations
- **Font Awesome** for icons

### **State Management & Data Fetching**

- **TanStack Query (React Query)** for server state management
- **React Hook Form** with Zod validation
- **Server Actions** for form handling

### **Backend & API**

- **Next.js API Routes** for backend functionality
- **Nodemailer** for email services
- **JOSE** for JWT token management

### **Development Tools**

- **TypeScript** for type safety
- **ESLint** for code quality
- **CSSnano** for CSS minification
- **Autoprefixer** for CSS compatibility

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm, yarn, pnpm, or bun

### Installation

**Clone the repository**

**Install dependencies**

**Set up environment variables**  
Create a `.env.local` file in the root directory:

**Run the development server**

**Open your browser**  
Navigate to [http://localhost:3000](http://localhost:3000) (or the port shown in terminal)

## 📁 Project Structure

```
autodemo1/
├── app/                    # Next.js App Router pages
│   ├── about-us/          # About Us page
│   ├── api/               # API routes
│   │   ├── company/       # Company data API
│   │   └── vehicles/      # Vehicle data APIs
│   ├── contact/           # Contact page
│   ├── services/          # Services page
│   └── vehicles/          # Vehicle pages
│       └── [id]/         # Dynamic vehicle detail pages
├── components/            # Reusable UI components
│   ├── layout/           # Layout components (Header, Footer, etc.)
│   ├── providers/        # Context providers
│   └── ui/               # UI components (Button, Input, Modal, etc.)
├── constants/            # Application constants
├── features/             # Feature-based components
│   ├── contact/          # Contact form functionality
│   ├── partners/         # Partner showcase
│   ├── services/         # Services display
│   └── vehicles/         # Vehicle-related features
├── hooks/                # Custom React hooks
├── lib/                  # Utility libraries
├── types/                # TypeScript type definitions
└── utils/                # Utility functions
```

## 🎨 Key Components

### **Vehicle Features**

- `VehicleGrid` - Grid layout for vehicle listings
- `VehicleItem` - Individual vehicle card component
- `VehicleDetail` - Detailed vehicle information page
- `VehicleImageSlider` - Image gallery with lightbox
- `Filters` - Advanced filtering system

### **UI Components**

- `Modal` - Reusable modal component
- `Button` - Customizable button component
- `Input` - Form input with validation
- `Spinner` - Loading indicator
- `NavLink` - Navigation link with hover effects

### **Layout Components**

- `Header` - Site header with logo and company data
- `Footer` - Site footer with social links
- `Navbar` - Main navigation
- `BgImage` - Dynamic background images

## 🔧 Available Scripts

```
# Development
npm run dev          # Start development server with Turbopack

# Production
npm run build        # Build for production
npm run start        # Start production server

# Code Quality
npm run lint         # Run ESLint
```

## 🌐 Deployment

### **Vercel (Recommended)**

1.  Push your code to GitHub
2.  Connect your repository to Vercel
3.  Add environment variables in Vercel dashboard
4.  Deploy automatically

### **Other Platforms**

The app can be deployed to any platform that supports Next.js:

- Netlify
- AWS Amplify
- Railway
- DigitalOcean App Platform

## ♿ Accessibility Features

- **ARIA Labels** - Comprehensive labeling for screen readers
- **Keyboard Navigation** - Full keyboard accessibility
- **Focus Management** - Proper focus indicators and management
- **Semantic HTML** - Proper heading structure and landmarks
- **Color Contrast** - WCAG compliant color schemes
- **Screen Reader Support** - Optimized for assistive technologies

## 🚀 Performance Optimizations

- **Dynamic Imports** - Lazy loading of heavy components
- **Image Optimization** - Next.js Image component with lazy loading
- **CSS Minification** - Production CSS optimization
- **Font Optimization** - Google Fonts with display swap
- **Bundle Splitting** - Automatic code splitting
- **Caching** - React Query for efficient data caching

## 🤝 Contributing

1.  Fork the repository
2.  Create a feature branch (`git checkout -b feature/amazing-feature`)
3.  Commit your changes (`git commit -m 'Add some amazing feature'`)
4.  Push to the branch (`git push origin feature/amazing-feature`)
5.  Open a Pull Request

## 📄 License

This project is private and proprietary. All rights reserved.

## 📞 Support

For support or questions, please contact us through the contact form on the website or reach out to the development team.

---

**Built with ❤️ using Next.js, React, and TypeScript**

```
npm run dev
# or
yarn dev
# or
pnpm dev
```

```
# Email configuration
SMTP_HOST=your-smtp-host
SMTP_PORT=587
SMTP_USER=your-email@example.com
SMTP_PASS=your-email-password

# JWT secret
JWT_SECRET=your-jwt-secret
```

```
npm install
# or
yarn install
# or
pnpm install
```

```
git clone <repository-url>
cd autodemo1
```
