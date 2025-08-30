# Qayaa — Ready-to-host Ecommerce (Demo)

Minimal, elegant womenswear storefront built with **Vite + React + Tailwind**.  
Includes: Shop, Product view, Cart, Checkout, and Admin Dashboard (products CRUD, orders, analytics).  
Data persists to `localStorage` for demo purposes.

## Run locally
```bash
npm install
npm run dev
```

## Build for hosting
```bash
npm run build
```
This creates a `dist/` folder. Deploy that folder to **Vercel**, **Netlify**, **Cloudflare Pages**, or any static host.

## Admin (demo)
Click **Admin** → password `qayaa` → manage products & orders.

## Customize theme
Edit `tailwind.config.js` colors and `src/App.jsx` content/images.
