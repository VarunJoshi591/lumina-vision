# 👁️ Lumina Vision — Cinematic Visual Intelligence Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Stage: Production SaaS](https://img.shields.io/badge/Stage-SaaS%20Ready-purple.svg)]()

**Lumina Vision** is an ultra-premium, cinematic landing page and interactive sandbox built for modern AI visual intelligence platforms. It features high-fidelity visual telemetry simulation, real-time client-side interactive configurations, and premium SaaS-level user journeys.

Designed to impress at first glance, the site leverages cutting-edge web aesthetics including fluid glassmorphism, responsive grid layouts, and custom-tailored micro-animations.

---

## ✨ Features

### 🎮 1. Interactive Vision Sandbox (`#sandbox`)
* **Real-time Presets:** Test-drive computer vision outputs on simulated feeds including **Logistics Warehouse**, **Smart City Traffic**, and **Assembly Quality**.
* **Live Controls:** Dynamically adjust the confidence threshold slider and inspect real-time telemetry changes.
* **Visual Overlays:** Toggle Bounding Boxes, Object Labels, and Thermal Heatmaps client-side.

### 🌐 2. Live Global Edge Network Monitor (`#network`)
* **Interactive Diagnostic Ping:** Trigger a cascading telemetry ping across worldwide server clusters (US-East-1, EU-West-2, AP-South-1, AP-Northeast-1).
* **Simulated Telemetry:** Dynamic indicators representing active stream connections, throughput latency, and live server load.

### 💳 3. Dynamic Subscription & Pricing Matrix (`#pricing`)
* **Billing Cycle Slider:** Toggle between Monthly and Yearly subscriptions with smooth CSS transitions.
* **Auto-Recalculation:** Interactive price adjustments and discount labels instantly reflected in the UI.
* **Premium Design:** Glassmorphic card styling, gradient headers, and a prominent glowing badge for the recommended plan.

### ❓ 4. Elastic FAQ Accordion (`#faq`)
* **Dynamic height Transition:** Fully responsive drawers utilizing `.scrollHeight` logic for flawless expanding/collapsing animations.
* **SVG Transformations:** Visual indicator rotates 45 degrees smoothly when active.

### 🎨 5. Cinematic UX & Styling System
* **Dual-Theme Engine:** Toggle between a rich cinematic dark mode and a clean light mode seamlessly.
* **Cursor Follower:** Dual-stage tracking cursor (inner dot and outer glowing ring) reacting dynamically to hoverable elements.
* **Curated Typography:** Premium font pairing using **Syne** for headings and **Inter** for clean readability.
* **Lightweight:** No external UI frameworks or heavy libraries. Fully optimized vanilla HTML, CSS, and JS.

---

## 🛠️ Technology Stack

* **Structure:** Semantic HTML5
* **Styling:** Custom CSS Variables with custom responsive layouts
* **Interactivity:** Modern Vanilla JavaScript (ES6+)
* **Icons:** Custom Inline SVGs for fast, crisp resolution

---

## 🚀 Getting Started

Lumina Vision is completely client-side and requires no complex backend installations.

### Running Locally

#### Option A: Quick Launch
Simply double-click the `index.html` file in your directory to open the application in any modern web browser.

#### Option B: Local Server (Recommended for asset loading)
To avoid local file protocol (`file://`) restrictions with asset resolution, run a local development server:

* **Using Python:**
  ```bash
  python -m http.server 8000
  ```
  Then open `http://localhost:8000` in your browser.

* **Using Node (npx):**
  ```bash
  npx serve .
  ```

---

## 📁 File Structure

```text
lumina-vision/
├── index.html              # Core application code (HTML, CSS variables, & Javascript logic)
├── smart_city_traffic.png  # High-fidelity traffic telemetry visual asset
├── .gitignore              # Git ignore rules
└── README.md               # Project documentation (this file)
```

---

## 🔒 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
