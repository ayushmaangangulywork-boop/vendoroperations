# FIIRS — FMCG Inventory Intelligence & Replenishment System

FIIRS is a self-developed portfolio project that models how an FMCG distribution business can monitor inventory, analyse supplier performance, track purchase orders, identify operational exceptions, and prioritise replenishment decisions in one interface.

## 🚀 Live Demo

**[Open Vendor Operations Intelligence System](https://ayushmaangangulywork-boop.github.io/FMCG-Inventory-Intelligence-Replenishment-System/)**

> **Portfolio disclaimer:** FIIRS uses a fictional FMCG business scenario and a synthetic dataset. Company names, locations, products, suppliers, purchase orders, and financial figures are fictional. This project is for demonstration and learning purposes; it is not a production deployment.

## Business context

FMCG operations typically involve many SKUs, suppliers, warehouses, stock movements, and purchase orders. Fragmented visibility can contribute to stockouts, low stock, excess inventory, slow-moving stock, and delayed deliveries.

FIIRS brings these operational views together so a user can review inventory health, supplier delivery performance, replenishment priorities, and exception items.

## What the application includes

- **Executive dashboard** with KPI cards, inventory-health summaries, management insights, and charts for category, warehouse, supplier, movement, and ABC views.
- **Inventory overview** with category/status/search filters, inventory value, inventory days, reorder levels, target stock, supplier details, and CSV export.
- **Product / SKU master** for product, category, unit-cost, safety-stock, reorder-level, target-stock, consumption, and supplier information.
- **Stock movements** covering sales, receipts, purchases, returns, adjustments, and transfers, with filtering and CSV export.
- **Purchase-order tracking** for ordered, received, pending, expected/actual delivery, delay days, fill rate, and status.
- **Supplier performance** scorecards using on-time delivery, fill rate, average lead time, delayed purchase orders, score, and rating.
- **Replenishment analysis** that calculates `Recommended Qty = Target Stock − Current Stock` and assigns `URGENT`, `REPLENISH NOW`, or `REVIEW` priorities.
- **Stockout risk** thresholds: critical at 3 or fewer inventory days, high at 7 or fewer, and medium at 14 or fewer.
- **Slow-moving inventory**, **excess inventory**, and **ABC inventory classification** views.
- **Reports** for executive inventory, replenishment, stockout risk, slow-moving inventory, supplier performance, ABC analysis, excess inventory, and inventory movements.

## Technology

- HTML
- CSS
- JavaScript
- React 18 (CDN)
- ReactDOM (CDN)
- Babel Standalone (CDN)
- Chart.js 4 (CDN)

The project is a single-page, client-side application. The synthetic data is defined within `index.html`; there is no database, API, backend service, or deployment configuration in this repository.

## Run locally

1. Clone or download this repository.
2. Open `index.html` in a modern web browser.
3. Use one of the sample accounts shown on the login screen.

Because React, Babel, Chart.js, and the fonts load from public CDNs, an internet connection is needed for the application to load those resources.

## Repository structure

```text
.
├── index.html       # Complete FIIRS application, styles, and synthetic dataset
├── README.md        # Project overview and usage notes
└── .gitignore       # Common local-file exclusions
```

## Scope and interpretation

FIIRS supports portfolio-level exploration of FMCG inventory, supplier, purchase-order, and replenishment concepts. The generated figures and recommendations should be interpreted only within the fictional scenario represented by the in-app synthetic data.

## Suggested GitHub metadata

**Repository name:** `FMCG-Inventory-Intelligence-Replenishment-System`

**Description:** FMCG inventory intelligence system for stock monitoring, supplier performance, replenishment analysis, purchase orders, ABC analysis, and operational exception tracking.

**Topics:** `fmcg`, `inventory-management`, `supply-chain`, `supplier-management`, `inventory-analytics`, `replenishment`, `operations-analytics`, `business-analytics`, `data-analytics`, `javascript`, `html`, `css`, `chartjs`
