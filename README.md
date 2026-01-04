# Vantage

**The Wealth Operating System.**

Vantage is a privacy-first, zero-friction financial tracker built on the **65-35 Rule**. Designed with a minimalist "Obsidian" dark mode interface, it effortlessly separates your **Needs**, **Wants**, and **Future Investments**.

---

## Overview

Unlike bloated finance apps that require bank logins and monthly subscriptions, Vantage runs entirely in your browser and saves data locally to your device. It is designed for speed, clarity, and absolute privacy.

---

## Core Philosophy: The 65-35 Protocol

Vantage automates the financial discipline required to build wealth by segmenting every rupee of income into three non-negotiable buckets:

1.  **Needs (65%):** Essential living expenses (Rent, Food, Utilities).
2.  **Futures (35%):** Wealth generation (SIPs, Stocks, Gold).
3.  **Wants (0%):** Discretionary spending is restricted until income grows.

---

## Key Features

### 1. Privacy By Design
* **No Login Required:** Start tracking immediately.
* **No Servers:** Your financial data never leaves your device.
* **Local Storage:** Data is persisted securely in your browser's local storage.

### 2. Obsidian UI
A stunning, high-contrast dark mode interface featuring:
* Glassmorphism effects.
* Neon accent gradients for visual hierarchy.
* "Midnight Obsidian" color palette (`#050505` background).

### 3. Advanced Wealth Tools
* **Global Stash:** Track your "Net Worth" across months.
* **Smart Deductions:** Deduct expenses directly from your savings stash without impacting your monthly budget limits.
* **Time Travel:** A custom date picker allows you to manage past data or plan for future months.
* **Data Sovereignty:** Full JSON Export/Import functionality ensures you can back up your data or migrate between devices.

### 4. Responsive Architecture
* **Desktop:** A dual-pane dashboard with a sticky sidebar for high-level metrics.
* **Mobile:** A sleek, app-like vertical feed optimized for touch interactions.

---

## Technical Architecture

Vantage is a high-performance Single Page Application (SPA) built with vanilla **HTML5**, **CSS3**, and **JavaScript**. It demonstrates high-fidelity UI implementation without the overhead of heavy frameworks.

### Technical Highlights

* **Zero-Dependency:** No React, Vue, or external libraries. Just pure, performant code (< 20kb).
* **Local Persistence:** Utilizes the browser's `localStorage` API for a persistent, client-side JSON database.
* **Responsive Layouts:** Uses CSS Grid and Flexbox with media queries to deliver two distinct UX layouts (Mobile Feed vs. Desktop Dashboard) from a single codebase.
* **State Management:** Custom vanilla JS state handling for real-time UI updates and reactive DOM manipulation.

---

## Installation & Usage

You can use Vantage directly via the web or run it locally on your machine.

### Method 1: Instant Access (GitHub Pages)
No installation is required. Click the link below to launch the app directly in your browser.

**[Launch Vantage Live](https://arnav-patange19.github.io/vantage/)**

### Method 2: Local Installation
If you prefer to run the code locally:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/arnav-patange19/vantage.git](https://github.com/arnav-patange19/vantage.git)
    ```
2.  **Open the application:**
    Simply open the `index.html` file in any modern web browser.
