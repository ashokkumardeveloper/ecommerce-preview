# Ecommerce Storefront & Admin Mockups

Interactive, mobile-first ecommerce **prototypes** for client review. Pure HTML/CSS/JS — no build step, no backend. Every layout is intentionally **buildable in Flutter** (Container, Row/Column, ListView, DataTable-style rows, `fl_chart` bars, Switch, Dropdown, Dialog).

**Live demo:** _(GitHub Pages URL will appear here once published)_

## What's inside

Open [`index.html`](index.html) — the launcher links to all apps.

### Storefronts (Meesho-style shopping apps)
| Store | Focus | Theme |
|-------|-------|-------|
| **BabyMall** | Kids — dresses, toys, footwear, wear | Sky blue + coral |
| **Kiddies Mate** | Kids (2nd brand) | Violet + orange |
| **Saliya** | Women — clothing, cosmetics, footwear, accessories | Plum + gold |

Each storefront includes: search, category tab, product grid, product detail (gallery, size/colour, related items, reviews), cart, checkout, account, my orders, and live order tracking. Fully responsive (separate mobile & desktop banners).

### Admin dashboards
`babymall/admin`, `kiddiesmate/admin`, `saliya/admin` — each with:
- **Dashboard** — KPIs, weekly sales chart, recent orders, low-stock alerts
- **Products** — search/filter, add/edit product (image + category + attributes: brand, colour, material, sizes, tags), stock badges, active toggle, delete
- **Orders** — filters, status dropdown, and a full **Order Detail** screen (items, customer, address, payment, timeline)
- **Inventory** — live stock adjust & restock

## Notes
- Prototype only — data lives in-memory and resets on refresh (no database).
- Product images load from the internet (LoremFlickr, with a Picsum fallback), so they're representative placeholders — swap in real catalogue photos anytime.
- Currency: ₹ (INR).
