# Receitas da Quinzena 🥘

A Tinder-style recipe meal‑planning app for Portuguese families living abroad.

Swipe through family recipes, plan your fortnightly menu, and discover UK ingredient substitutions — built for Diogo and Sara's household in London.

## Features

- **Recipe swiping** — swipe right to save, swipe left to skip
- **Fortnightly meal plans** — pick 6–8 recipes per session
- **UK ingredient substitutions** — Portuguese ingredients mapped to UK supermarket equivalents
- **Categories** — Ensopado, Sopa, Peixe, Carne, Vegetariano, Massa
- **PWA** — install on your phone, works offline with service worker caching
- **Supabase backend** — real-time sync across devices

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 19 + Vite |
| Backend | Supabase (PostgreSQL + Auth) |
| Styling | Custom CSS (dark Alentejo theme) |
| PWA | Workbox + vite-plugin-pwa |
| Fonts | Cormorant Garamond, DM Sans |

## Design

Dark terracotta-and-azulejo aesthetic inspired by Alentejo clay and Portuguese tiles. Warm text on deep charcoal backgrounds.

## Getting Started

```bash
npm install
npm run dev
```

Requires a Supabase project — set `VITE_SUPABASE_URL` and `VITE_SUPABASE_ANON_KEY` in `.env`.

## License

Private — family use.
