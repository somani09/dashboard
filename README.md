# Analytics Dashboard

A modern analytics dashboard built with Next.js 15, React 19, and TypeScript, featuring interactive charts and a glass morphism design.

## Features

- **Community Health Analytics** - Track and visualize community engagement metrics
- **Retention Insights** - Monitor user retention patterns and trends
- **Interactive Charts** - Dynamic line and bar charts with ApexCharts
- **Responsive Design** - Glass morphism UI with Tailwind CSS
- **Dark/Light Theme** - Theme switching with next-themes
- **Real-time Data** - Live chart updates and data visualization

## 🛠 Tech Stack

- **Framework**: Next.js 15 with Turbopack
- **Runtime**: React 19
- **Language**: TypeScript
- **Styling**: Tailwind CSS v4
- **Charts**: ApexCharts & React-ApexCharts
- **Icons**: React Icons
- **Theme**: next-themes
- **Package Manager**: pnpm

## Dashboard Sections

1. **Community Health** (`/community-health`) - Primary dashboard view
2. **Retention Insights** (`/retention-insights`) - User retention analytics

## Getting Started

First, install dependencies:

```bash
pnpm install
```

Then, run the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

The app will automatically redirect to the Community Health dashboard.

## Project Structure

```
app/
├── community-health/    # Community health analytics page
├── retention-insights/  # User retention analytics page
├── data-files/         # Mock data for charts and components
├── globals.css         # Global styles and CSS variables
├── layout.tsx          # Root layout with theme provider
├── page.tsx            # Root page (redirects to community-health)
└── utils.ts            # Utility functions

components/
├── apex-charts/        # Chart components using ApexCharts
├── buttons/            # Reusable button components
├── footer/            # Footer with analytics cards
├── icons/             # Custom SVG icons
└── layouts/           # Layout components with glass morphism

public/
└── static assets      # Images and SVG files
```

## Features in Detail

### Interactive Charts

- **Line Charts** - Smooth line visualizations with hover effects
- **Bar Charts** - Responsive bar charts with dynamic data
- **Chart Controls** - Toggle between chart types and cumulative view
- **Real-time Updates** - Charts respond to data changes instantly

### Glass Morphism Design

- **Glassmorphic Layout** - Modern glass-like UI components
- **Responsive Design** - Works seamlessly across all device sizes
- **Theme Support** - Dark and light mode with smooth transitions
- **Custom Animations** - Subtle hover and transition effects

### Dashboard Analytics

- **Summary Cards** - Key metrics at a glance
- **Campaign Activity** - Track engagement and performance
- **Footer Analytics** - Additional insights and suggestions

## 🛠 Available Scripts

```bash
# Development server with Turbopack
pnpm dev

# Production build
pnpm build

# Start production server
pnpm start

# Run ESLint
pnpm lint
```

## Deployment

This app is optimized for deployment on Vercel. Simply connect your GitHub repository to Vercel for automatic deployments.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/somani09/dashboard)

## Learn More

- [Next.js Documentation](https://nextjs.org/docs) - Learn about Next.js features and API
- [ApexCharts Documentation](https://apexcharts.com/docs/) - Interactive chart library
- [Tailwind CSS](https://tailwindcss.com/docs) - Utility-first CSS framework
- [React 19](https://react.dev/blog/2024/04/25/react-19) - Latest React features
