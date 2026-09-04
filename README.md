# BUSINESSOS — Your Business. Your Web App. Anywhere.

A **fully interactive, single-file web-app demo** built for **Oceanmonks** to show
how an affordable custom business application can replace Excel sheets,
WhatsApp messages and paperwork.

- **Zero dependencies, zero build** — one `index.html` (~310 KB) with all CSS + JS inline.
- Runs anywhere: double-click the file, or serve it (`npx serve` / GitHub Pages / Vercel / Netlify).
- All demo data lives in `localStorage`, so every change persists during the session.
- Reset anytime: **Profile → Reset demo data** or **Settings → Data & storage → Danger zone**.

## First run

1. Open `index.html`.
2. Choose your interface look — **Minimal** (monochrome icons) or **Colorful icons** (recommended).
3. You land on the **Dashboard** — no logins, it's a demo.

> Tip: open **DEMO MODE** (top bar) for a short tour of the demo story.

## The demo story (show this to a client)

1. **Products** → Add a product (sets price + opening stock + minimum stock).
2. **Inventory** → Adjust stock, watch history log every movement.
3. **Customers** → Add a customer with GSTIN, address and notes.
4. **Quotations** → Build a multi-line quotation (auto subtotal, discount, GST, total) → Preview → Send.
5. **Convert to Order** → stock is **deducted automatically**, an order with a full
   timeline is created, history + notifications are written, and the **dashboard updates**.
6. **Reports** → Generate Sales / Inventory / Customer / Order / Quotation reports,
   filter Today → Custom range, **Export CSV** or **Print**.

## What's inside

| Module | Highlights |
| --- | --- |
| Dashboard | KPI cards (real counts + 30-day trends), quick actions, Sales Overview chart (Today/Week/Month/Year), Top Products, Inventory donut, Recent quotations/orders, Low-stock list, Access-from-anywhere card |
| Quotations | Maker with searchable product lines, live ₹ totals, Save Draft / Preview / PDF (print dialog) / Share link / Send, duplicate, delete, **Convert to Order** |
| Products | CRUD, search, status filters, sort, SKU validation, supplier/category catalogue |
| Inventory | Add/Remove/Adjust stock, full movement history (prev → new, reason, by whom), value at cost, low/out statuses |
| Customers | CRM stats, searchable table, profile modal with orders, quotations, spend, recent activity |
| Orders | Create order, 6 statuses + payment tracking, record payment, timeline, cancel guard |
| Data Sheets | 6 seeded templates (Sales Tracker, Employee List, Supplier List, Expense Tracker, Lead Tracker, Daily Transactions) + custom sheets; add/delete rows, add/rename columns, cell editing, search, sort, CSV export |
| Reports | 5 report types, Today/Week/Month/Year/Custom ranges, trend charts, top products/customers, export & print |
| Employees | Roles (Owner→Employee), add/edit/deactivate, reset password, per-module permission matrix (View/Create/Edit/Delete/Export) that actually changes the sidebar & actions |
| Settings | Theme builder with **live preview** (colour pickers, radius, fonts, card/button style), preset themes, **Theme library** (save/apply/edit/duplicate/delete), workspace theme rules (force company vs employee personal themes), **Business Branding** (logo upload → appears on quotations/PDFs), Light/Dark/System, **Plan & Storage** (50 MB free, admin overview), Reset Demo Data |
| Top bar | Global search across products/customers/quotes/orders, notifications, DEMO MODE, business selector, profile menu with **demo user switcher** (see role-based permissions live) |

Design system: Oceanmonks palette (#2BD367 primary, #050505 / #123D27 dark, light grays),
colour used deliberately for icons/status only — including a **Minimal** icon mode.

## To make it yours (the Oceanmonks pitch)

BUSINESSOS is a template for **one real productised idea**: Oceanmonks ships
"BUSINESSOS as a Service" — every new workspace gets **50 MB free**, owners/admins
see and control all data, and paid plans add storage, multi-branch sync, GST
e-invoicing and WhatsApp quotation sending. Each client gets their own branding,
their own modules, deployed for a fraction of what off-the-shelf ERPs cost.
