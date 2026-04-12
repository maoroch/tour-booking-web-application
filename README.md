# Blue Star Tours

**Blue Star Tours** is a modern travel and tour booking web application built with [Next.js](https://nextjs.org). It allows users to browse tours, filter by destination, date, and number of passengers, and explore travel packages from around the world.

## Key Features

- 🔍 **Smart Tour Search** — Filter tours by country, departure date, and number of passengers directly from the hero banner.
- 🗺️ **Destinations** — Browse curated travel destinations with rich visuals.
- 🏆 **Featured Tours** — Highlight the most popular and exciting travel packages.
- 📋 **Detailed Tour Pages** — Each tour includes full descriptions, itinerary, pricing, and booking options.
- 🌟 **Testimonials** — Real customer reviews to build trust and inspire new travelers.
- 📰 **Travel Blog** — Articles and travel tips to help users plan their trips.
- 👥 **Team Section** — Meet the professional guides and travel experts behind Blue Star Tours.
- 📍 **Activities & Experiences** — Browse available activities at each destination.
- 📞 **Contact Page** — Easy-to-use contact form for inquiries and bookings.
- ⚡ **24/7 Support** — Round-the-clock customer support for all travelers.
- 💰 **Best Price Guarantee** — Competitive pricing with a best-price promise.
- 🎨 **Multiple Homepage Layouts** — Three distinct homepage designs for flexible presentation.
- 📱 **Fully Responsive** — Optimized for all screen sizes using Bootstrap 5.

## Tech Stack

- **Framework**: [Next.js 16](https://nextjs.org) with TypeScript
- **UI**: [React 19](https://react.dev), [Bootstrap 5](https://getbootstrap.com), [React Bootstrap](https://react-bootstrap.github.io)
- **Carousel**: [React Slick](https://react-slick.neostack.com)
- **Icons**: [Bootstrap Icons](https://icons.getbootstrap.com)

## Getting Started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
src/
├── app/
│   ├── (home1)/          # Default homepage layout
│   ├── (innerpage)/      # Inner pages (About, Tour, Blog, Contact, etc.)
│   ├── home2/            # Alternative homepage layout 2
│   ├── home3/            # Alternative homepage layout 3
│   ├── Components/       # Shared UI components
│   └── assets/           # Static assets
└── lib/                  # Utility functions and helpers
```

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start the development server with Turbopack |
| `npm run build` | Build the app for production |
| `npm run start` | Start the production server |
| `npm run lint` | Run ESLint |

## Deploy on Vercel

The easiest way to deploy this app is to use the [Vercel Platform](https://vercel.com/new). Check out the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
