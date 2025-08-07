# PWA Finance App

A mobile-first Progressive Web App for managing personal finances, budgets, and micro‑lending in a simple, offline-friendly way.

## Why build a finance PWA?

Managing money in emerging markets is often messy: spreadsheets don’t sync, mobile apps need constant internet, and micro‑lending is often informal. This project aims to provide an easy, cross-platform way to:

- Track expenses and income categories.
- Set spending budgets and receive smart alerts when you’re over or under.
- Manage micro‑loans between friends or community groups.
- Work offline-first, syncing automatically when back online.

By building as a PWA, we ensure the experience feels like a native app while staying accessible across devices and connections.

## Tech Stack

- **Next.js** & **React** – for building the core UI.
- **Supabase** – Postgres database with real-time sync and auth.
- **Tailwind CSS** – rapid styling and responsive design.
- **PWA APIs** – service workers, caching, offline storage.
- **OpenAI API** – optional AI assistant for budgeting advice.
- **Node.js** – backend functions for calculations and sync.

## Features (Planned)

- Transaction logging with category tagging.
- Budget planner with progress bars and notifications.
- Micro‑lending module for tracking loans and repayments.
- Offline caching and background sync via service workers.
- Export to CSV/Excel for audits.
- Localization for Indian languages.

## Roadmap

| Phase | Goals |
|------|------|
| **MVP** | Basic transaction logging, category totals, offline cache |
| **v1.0** | Budget planner, export feature, local language support |
| **v1.5** | Micro‑lending module, PWA install prompt and push notifications |
| **v2.0** | AI budgeting assistant, machine learning insights |

## Contributing

This project is in active development. Feel free to fork, open issues, or submit pull requests. We welcome contributions focused on UX/UI improvements, new features, or bug fixes.

## License

This repository uses the MIT License. See the `LICENSE` file for details.
