## Features

- **11 fully built pages** — Dashboard, Accounts, Transactions, Transfers, Cards, Crypto, Analytics, Investments, Budgets, Settings, Notifications
- **Crypto dashboard** — Candlestick chart, live portfolio, trade form, market overview with 8 coins
- **Drag-and-drop dashboard** — Rearrange widgets with dnd-kit, persisted to localStorage
- **Interactive credit cards** — 3D flip animation, freeze toggle, virtual card generator
- **Live investment ticker** — Simulated real-time price updates with flash animations
- **Spending heatmap** — GitHub-style 365-day calendar visualization
- **Actionable notifications** — Accept/decline money requests and device authorization inline
- **Smart analytics** — Category drill-down donuts, recurring charge detector, AI insights
- **Budget tracking** — Animated SVG progress rings, savings goals, month projection
- **Quick transfers** — Contact selector with send simulation
- **Auth pages** — Sign in / sign up with animated 3D globe, powered by [Clerk](https://clerk.com)
- **Dark mode** — Full dark/light/system theme support
- **Responsive** — Works on desktop, tablet, and mobile

## Pages

| Page | Description |
|------|-------------|
| `/dashboard` | Financial overview, wallet cards, quick transfer, spending limit, money movement |
| `/accounts` | Linked bank accounts with balances, add account flow |
| `/transactions` | Searchable table with filters, expandable rows, bulk CSV export |
| `/transfers` | Send/receive/scheduled transfers with stats and quick send |
| `/cards` | 3D flip card, freeze/unfreeze, spending controls, virtual card creator |
| `/analytics` | Spending heatmap, category breakdown, recurring charges, AI insights |
| `/crypto` | Candlestick chart, portfolio balance, top coins, trade form, market overview |
| `/investments` | Portfolio allocation, holdings with sparklines, live ticker, watchlist |
| `/budgets` | Budget rings, savings goals, spending calendar, month projection |
| `/settings` | Profile, security, notifications, billing, appearance |
| `/notifications` | Filterable notification feed with dismiss animations |
| `/sign-in` | Auth page with animated 3D globe, social login, powered by Clerk |
| `/sign-up` | Registration with name, email, password, terms acceptance |

## Tech Stack

| | Technology |
|---|---|
| Framework | [Next.js 16](https://nextjs.org) (App Router) |
| UI | [shadcn/ui](https://ui.shadcn.com) |
| Styling | [Tailwind CSS v4](https://tailwindcss.com) |
| Charts | [Recharts](https://recharts.org) |
| Animations | [Motion](https://motion.dev) |
| Drag & Drop | [@dnd-kit](https://dndkit.com) |
| Auth | [Clerk](https://clerk.com) |
| 3D Globe | [three-globe](https://github.com/vasturiano/three-globe) + [Aceternity UI](https://ui.aceternity.com) |
| Icons | [Lucide React](https://lucide.dev) |
| Language | TypeScript |