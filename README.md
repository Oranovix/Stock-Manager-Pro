<div align="center">

<a href="README.md"><img src="assets/lang/en-active.svg" height="40" alt="English"/></a>&nbsp;<a href="README.de.md"><img src="assets/lang/de.svg" height="40" alt="Deutsch"/></a>&nbsp;<a href="README.ar.md"><img src="assets/lang/ar.svg" height="40" alt="العربية"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0A0A,55:047857,100:10B981&height=190&section=header&text=Stock%20Manager%20Pro&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=46" width="100%" alt="Stock Manager Pro — professional desktop inventory management for Windows"/>

**Professional desktop inventory management for Windows**

Local-first · barcode-aware · multi-PC cloud sync · trilingual (EN / DE / AR)

[![Latest release](https://img.shields.io/github/v/release/Oranovix/stock-manager-pro?style=flat-square&label=Download)](https://github.com/Oranovix/stock-manager-pro/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?style=flat-square&logo=windows)](https://github.com/Oranovix/stock-manager-pro/releases/latest)
[![License](https://img.shields.io/badge/License-Proprietary-blue?style=flat-square)](EULA.md)

[**⬇ Download the latest installer**](https://github.com/Oranovix/stock-manager-pro/releases/latest) · [Features](#-features) · [Screenshots](#-screenshots) · [Editions](EDITIONS.md) · [Changelog](CHANGELOG.md) · [Report a problem](https://github.com/Oranovix/stock-manager-pro/issues)

</div>

---

![Dashboard](assets/scr-dashboard.png)

## Overview

Stock Manager Pro is a professional, offline-first desktop inventory management application for small-to-medium repair shops, retail stores, and warehouses. It ships with a complete business operations suite — a full POS terminal, purchase-order lifecycle, stocktake audits, price lists, supplier CRM, multi-location stock, **IMEI-level phone-unit tracking**, and **14 branded PDF reports** — all built on a zero-freeze async engine with a clean, layered architecture. Data stays local by default, with **optional multi-PC cloud sync** when you need it.

Built for real shops that need to know **exactly what's in stock, what it's worth, and what sold today** — without a server, a subscription to someone else's cloud, or an internet connection.

- **Local-first.** Your data lives in a database file on your PC. The app is fully functional offline. Backups are one click, and exports (CSV/JSON) are always available.
- **Barcode everything.** Generate labels, scan with any USB scanner, and use the Quick-Scan workflow for receiving, selling, and stock checks.
- **Multi-PC cloud sync** (Pro). Two or more PCs share one live dataset — the shop counter and the back office always see the same stock.
- **Truly multilingual.** Every screen in English, German, and Arabic (full RTL support), switchable at runtime.

---

## ✨ Features

### Core Inventory
- Unified inventory across categories, part types, phone models, and colour variants
- **Matrix grid view** — spreadsheet-style bulk stock across model × part-type × colour, with a frozen model column, sticky headers, and per-part-type value totals
- **Phone units (IMEI tracking)** — track whole devices individually by IMEI: storage, condition, battery %, buy/sell price, status (in stock / sold / reserved), barcode labels, sold-history and a full audit log *(optional module)*
- Stock In / Out / Adjust with timestamped notes and full undo / redo
- Per-item minimum-stock thresholds with real-time low-stock alerts
- Product photos, expiry dates, and warranty tracking per item
- Barcode generation (Code128/EAN) and USB scanner interception

### Business Modules
| Module | Highlights |
|---|---|
| **Sales / POS** | Cart-based POS, customer lookup, discounts, PDF receipts, edit/void with automatic stock reversal |
| **Phones (IMEI)** | Whole-device inventory by IMEI — brand × model stock grid, scan-to-sell, reserve, barcode labels, sold history |
| **Purchase Orders** | DRAFT → SENT → PARTIAL → RECEIVED lifecycle, auto stock-in on receipt |
| **Returns** | RESTOCK or WRITE_OFF actions, refund tracking, sale linkage |
| **Suppliers** | Supplier CRM, cost prices, lead days, linked inventory items |
| **Price Lists** | Create, draft, activate and bulk-apply pricing configurations |
| **Audit / Stocktake** | Cycle-based counted vs system qty comparison with variance reporting |
| **Customers** | Customer profiles linked to sales and purchase history |
| **Locations** | Multi-location stock with transfers between warehouse positions |
| **Reports** | 14 branded PDF reports — inventory, valuation (at cost), low stock, transactions, sales, category performance, audit, **phone inventory & sold history**, barcode labels, and more |

### Platform
- **Zero-freeze UI** — every database operation runs off the main thread; the interface never blocks regardless of dataset size
- **Optional cloud sync** — share one live dataset across multiple PCs; no server to run, opt-in per install
- **Optional modules** — shop-specific features (e.g. the Phones / IMEI tracker) are opt-in per install via Shop Settings → Modules
- **Multilingual** — English, German (DE), Arabic (AR) with live switching and full RTL layout
- **Four themes** — Dark, Light, Pro Dark (emerald/charcoal), Pro Light (emerald/white)
- **Excel-like zoom** — Ctrl+Scroll / Ctrl+Plus/Minus zoom (50–200%) with footer slider
- **Auto-updater** — manifest-based version check with SHA256 verification
- **Auto-backup** — scheduled backup with configurable retention
- **Undo / redo** — reverse any stock or phone-status operation
- **Offline-first** — local database (WAL), no telemetry; cloud sync is strictly opt-in

---

## 📸 Screenshots

> Screenshots use a demo dataset.

### Analytics Dashboard
Real-time KPI cards (stock value at cost, revenue, transactions, low stock), a stock-health donut, value-by-brand bars, and a brand × part-type valuation pivot — all loaded asynchronously off the UI thread.

![Analytics Dashboard](assets/scr-dashboard.png)

---

### Matrix View
The core workflow — spreadsheet-style bulk stock across model × part-type × colour, with a frozen model column, per-part-type value totals, and Low / Out / Reorder filters.

![Matrix View](assets/scr-displays.png)

---

### Inventory
Searchable, filterable product table with KPI overview cards (units, low / out of stock, inventory value), status badges, and inline +1 / −1 quick-stock actions.

![Inventory](assets/scr-inventory-v2.png)

---

### Phones — IMEI tracking
Whole-device inventory tracked by IMEI: a brand × model stock grid by storage, KPIs (total / in stock / sold / avg battery / stock value), scan-to-sell, reserve, and barcode labels. *(Optional module.)*

![Phones](assets/scr-phones.png)

---

### Sales & POS
Cart-based point-of-sale with product picker, customer lookup, discounts, automatic PDF receipts, and edit / void with stock reversal.

![Sales & POS](assets/scr-sales.png)

---

### Reports
14 professional, branded PDF reports for **parts and phones** — inventory, valuation (at cost), low stock, transactions, sales, category performance, audit sheets, phone inventory & sold history, expiring stock, and barcode labels.

![Reports](assets/scr-reports.png)

---

### Transactions
Paginated stock-movement audit log with an IN / OUT / ADJUST / Net summary strip, debounced filters, and Load-More pagination.

![Transactions](assets/scr-transactions.png)

---

### Purchase Orders
Full PO lifecycle from DRAFT through SENT → PARTIAL → RECEIVED. Receiving a PO automatically triggers a stock-in.

![Purchase Orders](assets/scr-purchase-orders.png)

---

### Suppliers
Supplier CRM with contact details, rating, linked inventory items, and open purchase-order count per supplier.

![Suppliers](assets/scr-suppliers.png)

---

### Audit & Stocktake
Cycle-based stocktake with item-by-item counted-qty entry, system-vs-counted variance reporting, and a completion summary.

![Audit](assets/scr-audit.png)

---

### Price Lists
Create and manage pricing configurations; apply a bulk percentage markup or push a list straight to live inventory.

![Price Lists](assets/scr-price-lists.png)

---

### Returns
Process returns with RESTOCK or WRITE_OFF actions — reverses the original transaction and records the refund amount.

![Returns](assets/scr-returns.png)

---

### Quick Scan
USB barcode-scanner interception with command barcodes (TAKEOUT / INSERT / CONFIRM) for hands-free stock counting.

![Quick Scan](assets/scr-quickscan.png)

---

### Barcode Generator
Generate and export Code128 / EAN barcodes; batch-print labels for new stock.

![Barcode Generator](assets/scr-barcode.png)

---

## 🖥️ System Requirements

| | |
|---|---|
| **OS** | Windows 10 or Windows 11 (64-bit) |
| **RAM** | 512 MB minimum · 2 GB recommended |
| **Disk** | 250 MB application + database storage |
| **Admin rights** | Not required |
| **Internet** | Not required for daily use (update check and cloud sync are opt-in) |

---

## Editions

| | **Free** | **Pro** |
|---|---|---|
| Core inventory, matrix, barcodes, POS | ✅ | ✅ |
| PDF reports | 3 core | **All 14** |
| PCs / cloud sync | 1 PC, local | **Multi-PC shared cloud** |
| Phones / IMEI module | — | ✅ |
| Purchase orders, price lists, audits | Trial | ✅ |

Full comparison and commitments: [EDITIONS.md](EDITIONS.md)

---

## 📦 Install

1. [Download the latest `StockManagerPro-x.y.z-setup.exe`](https://github.com/Oranovix/stock-manager-pro/releases/latest)
2. Run the installer — existing data is preserved on updates
3. The app checks for updates automatically; every release is published here

Data is stored at `%LOCALAPPDATA%\StockPro\StockManagerPro\stock_manager.db` — no admin rights needed, no account, no internet required for daily use.

---

## 🚀 Quick Start

| Task | How |
|---|---|
| First-time setup | Complete the Setup Wizard on first launch |
| Add a product | `Ctrl+N` or **+ Add Product** button |
| Stock In | Select product → `Ctrl+I` |
| Stock Out | Select product → `Ctrl+O` |
| Adjust stock | Select product → `Ctrl+J` |
| Open POS | Navigate to **Sales / POS** → New Sale |
| Generate barcode | Right-click product → Generate Barcode or `Ctrl+B` |
| Export PDF report | Navigate to **Reports** or `Ctrl+P` |
| Admin settings | `Ctrl+Alt+A` or the ⚙ header icon |
| Switch language | Header language switcher (EN / DE / AR) |
| Undo last operation | Right-click transaction → Undo |
| Force refresh | `F5` |

---

## 🏗️ Architecture

Stock Manager Pro is built on a strictly layered architecture with a zero-freeze async engine — the UI never queries the database directly and never blocks.

```
┌──────────────────────────────────────────────────────────────┐
│  UI Layer  —  pages · components · dialogs · tabs · controllers │
├──────────────────────────────────────────────────────────────┤
│  Async Engine  —  WorkerPool · DataWorker · UpdateWorker      │
├──────────────────────────────────────────────────────────────┤
│  Service Layer  —  business logic (21 services)               │
├──────────────────────────────────────────────────────────────┤
│  Repository Layer  —  SQL-only data access (13 repositories)  │
├──────────────────────────────────────────────────────────────┤
│  Model Layer  —  pure domain dataclasses (13 models)          │
├──────────────────────────────────────────────────────────────┤
│  Core Layer  —  Database · Theme · i18n · Config · Logger     │
│  SQLite WAL · Schema V23 · 27 tables · optional cloud sync    │
└──────────────────────────────────────────────────────────────┘
```

**Zero-freeze async engine** — every database operation is routed off the main thread through a worker pool with keyed cancellation and debounced filter inputs. The main thread only ever applies results; it never queries. Theme changes are deferred to the next event-loop tick to eliminate any freeze on toggle.

**Optimised database** — thread-local connection pool, batch inserts, performance indexes, and tuned pragmas. A full automatic migration chain (Schema V1 → V23) runs on every startup, so upgrades never require manual data work. 27 tables cover inventory, sales, purchase orders, returns, suppliers, customers, locations, audits, price lists, phones (IMEI), and their audit logs.

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|---|---|---|
| UI Framework | **PyQt6** | Native desktop GUI |
| Database | **SQLite 3** (WAL + FK) | Local relational storage |
| PDF | **fpdf2** + **PyMuPDF** | Reports and receipts |
| Barcodes | **python-barcode** | Code128 / EAN generation |
| Images | **Pillow** | Product photos, icon handling |
| Packaging | **PyInstaller** | Windows executable |

---

## ⌨️ Keyboard Shortcuts

| Action | Shortcut | Action | Shortcut |
|---|---|---|---|
| New product | `Ctrl+N` | Generate barcode | `Ctrl+B` |
| Stock In | `Ctrl+I` | Export PDF report | `Ctrl+P` |
| Stock Out | `Ctrl+O` | Zoom in / out | `Ctrl+=` / `Ctrl+-` |
| Adjust stock | `Ctrl+J` | Reset zoom | `Ctrl+0` |
| Search | `Ctrl+F` | Admin settings | `Ctrl+Alt+A` |
| Delete product | `Del` | Force refresh | `F5` |

---

## 🔒 Data & Privacy

All data stays on your machine:

```
%LOCALAPPDATA%\StockPro\StockManagerPro\stock_manager.db
```

- No internet connection required (update check is opt-in)
- No telemetry, no user tracking; cloud sync is strictly opt-in (your own cloud database)
- Complete audit log of every stock movement
- Automatic backup with configurable retention
- SQLite WAL mode for crash safety

---

## 📈 Releases

Every release is built and published automatically here — installer, `update_manifest.json` (SHA256-verified), and changelog. The complete per-version history lives in **[CHANGELOG.md](CHANGELOG.md)**.

| Milestone | Highlights |
|---|---|
| **2.7.x** | Multi-PC cloud-sync hardening, replica-role fixes, release-pipeline automation |
| **2.6.x** | Cloud-sync enable fix, dashboard stock-health accuracy, refreshed screenshots |
| **2.5.x** | 📱 Phones (IMEI) module, optional cloud sync, 14 professional PDF reports, German-keyboard barcode round-trip fixes |
| **2.3.x** | Zero-freeze async engine, controller refactor, full business suite (POS, Purchase Orders, Returns, Suppliers, Audit, Price Lists, Customers, Locations) |
| **2.1 – 2.2** | Colour dimension in the matrix, barcode generator, Quick Scan workflow |
| **1.0.0** | Core inventory, barcode scanning, multilingual interface, offline SQLite |

---

## Support

- 🐛 [Report a bug](https://github.com/Oranovix/stock-manager-pro/issues/new?template=bug_report.md)
- 💡 [Request a feature](https://github.com/Oranovix/stock-manager-pro/issues/new?template=feature_request.md)
- 💼 Commercial licensing & multi-shop deployments: contact [Oranovix](https://github.com/Oranovix)

---

## 📄 License

Stock Manager Pro is commercial software © 2026 Oranovix / Abdullah Bakir.
The installers on this page are licensed under the [End-User License Agreement](EULA.md).
Your data always remains yours — export, backups, and read access work in every edition, licensed or not.

---

<div align="center">

**[Download](https://github.com/Oranovix/stock-manager-pro/releases/latest)** · **[Report a Bug](https://github.com/Oranovix/stock-manager-pro/issues)** · **[Request a Feature](https://github.com/Oranovix/stock-manager-pro/issues/new?template=feature_request.md)**

Happy Inventory Managing 🚀

</div>
