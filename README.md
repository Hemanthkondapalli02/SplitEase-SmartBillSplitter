🧾 SplitEase – Smart Bill Splitter

SplitEase is a modern, responsive bill-splitting web application that makes it easy to divide expenses among friends. It supports equal and custom splits, GST/tip calculation, UPI QR generation, QR scanning, and calculation history — all in a clean, minimal UI.

🚀 Features
💰 Smart Bill Splitting

Equal split among multiple people

Custom amount per person

Automatic rounding options:

Exact

Round to nearest ₹1

Round up

Round down

🧾 Category-Based Billing

Add preset categories (Food, Drinks, Travel, etc.)

Create custom categories with icons

Auto-sync category totals with bill amount

➕ Extras & Options

Tip calculation (10%, 15%, 18%, 20%, Custom)

GST/Tax toggle with custom percentage

Real-time calculation preview

🏦 UPI Payment Integration

Generate UPI QR code

Share QR as image

Copy UPI ID

WhatsApp share integration

Scan others' UPI QR codes using camera

🕐 History Management

Stores last 50 calculations

Reload previous bills

Delete individual records

Clear all history

🌗 Dark / Light Mode

Fully theme-based UI

Theme preference saved in localStorage

📱 Progressive Web App (PWA)

Service worker support

Installable on mobile

Offline-ready (if configured with sw.js)

🛠️ Tech Stack

HTML5

CSS3 (Custom Theming with Variables)

Vanilla JavaScript (ES6+)

QR Code Generation via qrcode.js

QR Scanning via:

BarcodeDetector API

Fallback to jsQR

LocalStorage for persistence

No frameworks. No backend. Fully client-side.

📷 Screens Overview

Split Bill page

UPI QR Generator

QR Scanner

History Page

Share Bill Image Generator

🔐 Data Storage

All data is stored locally in the browser using localStorage:

Theme preference

Bank/UPI details

Bill history

No external server or database is used.
