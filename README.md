# ☕ Web-Based POS and QR Ordering System for Coffee Lips

An integrated web application combining a public website, table-specific QR-based digital menu, customer ordering system, real-time kitchen/staff order queue, and point-of-sale (POS) billing system tailored for **Coffee Lips** cafe.

Developed as part of the **IS5109 - IS Project for Community** module at Sabaragamuwa University of Sri Lanka.

---

## 📌 Project Overview

Coffee Lips requires a seamless solution to manage dine-in ordering, preparation, and billing without manual delays. This system enables customers to scan table-specific QR codes, browse the digital menu, place orders directly from their mobile browsers, and keep track of their running bill. Cashiers and staff can manage active orders, update preparation states in real-time, record payments, and view detailed sales reports.

---

## ✨ Key Features

### 📱 Customer Features
- **Table QR Code Access:** No app installation required; scan and view the table-specific menu via mobile browser.
- **Digital Menu:** Browse categories, item descriptions, prices, and real-time availability.
- **Pay-After-Eating Model:** Group multiple orders under a single table visit and view the running total.
- **Order Tracking:** Track real-time order status updates (New, Preparing, Ready, Served).

### 👨‍🍳 Staff & Cashier Features
- **Order Management:** Real-time incoming order dashboard with status update capabilities.
- **POS & Billing:** Review final table visit totals, calculate tax/discounts, record cash/card payments, and generate digital receipts.
- **Table Visit Lifecycle:** Manage opened table visits, guest count, and close visits upon final settlement.

### 🛡️ Admin & Management Features
- **Menu & Category Management:** Add, edit, or toggle availability of menu items and categories.
- **Table & QR Management:** Generate unique, secure QR code links and manage physical dining tables.
- **Staff Management:** Role-based control and secure JWT authentication for staff/cashiers/admins.
- **Analytics & Reports:** Sales metrics, popular items, peak hours, and order summaries.

---

## 🛠️ Tech Stack & Requirements

### Software & Technologies
- **Frontend:** React.js (Responsive Mobile & Desktop UI)
- **Backend:** Python FastAPI (REST APIs, WebSockets)
- **Database:** PostgreSQL (Relational Data Storage)
- **Authentication:** JWT-based Token Authentication
- **Real-time Communication:** WebSockets (Live order updates)
- **Design & Testing:** Figma, Postman, VS Code, Git/GitHub

---

## 🧩 System Architecture & Modules

1. **Coffee Lips Website:** Public info, contact details, menu navigation.
2. **QR Code & Table Management:** Generate table tokens & QR links.
3. **Digital Menu:** Dynamic category and product display.
4. **Customer Ordering:** Interactive cart, special instructions, and order placement.
5. **Staff Order Management:** Kitchen dashboard & order status tracking.
6. **POS and Billing:** Running totals, cashier settlement, and digital receipts.
7. **Administration:** Inventory/menu items, staff accounts, role assignment.
8. **Reports and Analytics:** Daily/weekly sales, completed orders, performance metrics.

---

## ⚙️ Getting Started (Local Development)

### Prerequisites
- Python 3.10+
- Node.js 18+
- PostgreSQL installed and running

