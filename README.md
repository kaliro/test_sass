# Futuristic SaaS Analytics Dashboard

This example showcases a concept dashboard inspired by Baremetrics and Apple Vision Pro. It demonstrates a dark-themed, neon-accented UI with animated charts and glassmorphism-style panels.

## Features

- **Dark mode base** `#0E1117` with electric blue, violet, and mint green accents.
- **Glassmorphism cards** with soft shadows and subtle hover animations.
- **Real-time style charts** built with Chart.js, animating on load.
- **Minimal sidebar** using icon placeholders.
- **Typography** via [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) for a modern look.

## Key Sections

- **Overview** &mdash; bar/line chart mixing MRR, active users, and churn.
- **Revenue Breakdown** &mdash; pie chart illustrating plan or regional revenue.
- **Customer Insights** &mdash; line chart plotting ARPU and LTV trends alongside active users.
- **Forecasting** &mdash; projected growth curves with risk alert markers.

## Running locally

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the development server:
   ```bash
   npm start
   ```
3. Visit `http://localhost:3000` to view the dashboard.

The static assets live in the `public/` directory and are served by a tiny Express server defined in `server.js`.
