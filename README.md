# Officethree Technologies

Official website for **Officethree Technologies Private Limited** — a product studio building intelligent software across restaurants, creative AI, and sports analytics.

## Products

- **Amogha Cafe & Restaurant** — Full-stack restaurant operations platform with 10+ surfaces (ordering, KDS, POS, delivery, kiosk, analytics). Built on Firebase with Razorpay payments and Gemini AI.
- **Artigen** — AI-powered art community for generative art creation, sharing, and discovery with multi-model AI tools, social features, and a creator marketplace.
- **Sports Betting Analytics** — Quantitative edge-finding engine aggregating 20+ sportsbooks with XGBoost ML models and Kelly criterion sizing.

## Tech Stack

React, Next.js, TypeScript, Firebase, Node.js, Gemini AI, XGBoost, Razorpay

## Project Structure

```
├── index.html          # Main website (single-page)
├── privacy.html        # Privacy policy
├── terms.html          # Terms of service
├── 404.html            # Custom error page
├── sitemap.xml         # SEO sitemap
├── robots.txt          # Search engine directives
├── README.md           # This file
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Pages CI/CD
```

## Development

Open `index.html` in your browser. No build step required — this is a static site.

## Deployment

Automatic deployment to GitHub Pages via GitHub Actions on push to main branch. Can also be deployed to any static hosting provider (Netlify, Vercel, AWS S3, Cloudflare Pages).

## Contact Form Setup

The contact form uses [Web3Forms](https://web3forms.com/). To activate:

1. Get a free access key at web3forms.com
2. Replace `YOUR_WEB3FORMS_KEY` in index.html with your key

## License

Copyright 2026 Officethree Technologies Private Limited. All rights reserved.
