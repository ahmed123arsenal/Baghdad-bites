# 🍔 Baghdad Bites v3 — بغداد بايتس

> **AI-Powered Fast Food Radar for Baghdad, Iraq**  
> **رادار الوجبات السريعة المدعوم بالذكاء الاصطناعي في بغداد**

![Version](https://img.shields.io/badge/Version-3.0-ff6b35?style=for-the-badge&labelColor=1a0500)
![Language](https://img.shields.io/badge/Bilingual-AR%20%2F%20EN-ffd60a?style=for-the-badge&labelColor=1a0500)
![License](https://img.shields.io/badge/License-MIT-30d158?style=for-the-badge&labelColor=1a0500)
![No Dependencies](https://img.shields.io/badge/Dependencies-ZERO-5ac8fa?style=for-the-badge&labelColor=1a0500)

---

## 🌟 What's New in v3

| Feature | Description |
|---|---|
| 🌐 **Arabic / English Toggle** | Full RTL support with one click — every element translates |
| 🍔 **Food Background** | Animated floating food particles with rich red-orange gradient scene |
| 🪟 **iOS Glassmorphism** | Every panel, card, sidebar and modal uses backdrop-blur glass effect |
| 🎨 **New Color Palette** | Vibrant food-inspired reds, oranges, and yellows — brown removed entirely |
| 📐 **Full RTL Layout** | Sidebar, cards, modals, filters all flip correctly for Arabic |

---

## ✨ Features

- 🔍 **Live Search** — filters as you type in English or Arabic
- 🤖 **AI Search** — web-powered search for the latest Baghdad openings
- 📋 **3 View Modes** — Grid, List, Map
- ⭐ **Reviews & Ratings** — read and post reviews
- 📱 **Restaurant Detail Modal** — phone, address, delivery apps, socials
- 🗺 **Google Maps Integration** — get directions with one click
- 🔔 **New Opening Alerts** — banner notifications for latest arrivals
- 🛵 **Delivery Links** — Talabat & Lezzoo integration
- 📤 **Share** — native share sheet on mobile

---

## 🍽 Restaurants Tracked

| Restaurant | Status | Category |
|---|---|---|
| 🎸 Johnny Rockets | New 2023 | Burgers |
| 🍗 KFC Baghdad | Established | Chicken |
| 🍕 Pizza Hut Baghdad | Established | Pizza |
| 🍔 Hardee's Iraq | Established | Burgers |
| 🍩 Cinnabon Baghdad | New 2023 | Desserts |
| 🌶️ Chili's Baghdad | Recent | Casual Dining |
| ☕ Tim Hortons Iraq | New 2024 | Coffee |
| 🍕 Papa John's Baghdad | Recent | Pizza |

---

## 🚀 Live Demo

**[👉 baghdad-bites.github.io/bites](https://YOUR-USERNAME.github.io/baghdad-bites)**

---

## 📦 Quick Start

```bash
git clone https://github.com/YOUR-USERNAME/baghdad-bites.git
cd baghdad-bites
open index.html   # or just double-click it
```

No build step. No npm. No framework. **Pure HTML/CSS/JS.**

---

## 🗂 Project Structure

```
baghdad-bites/
├── index.html            ← Entire app (zero dependencies)
├── README.md             ← This file
├── LICENSE               ← MIT License
└── .github/
    └── workflows/
        └── deploy.yml    ← Auto-deploy to GitHub Pages
```

---

## 🧠 How the AI Search Works

The AI Search button sends your query to the Anthropic Claude API with the `web_search` tool enabled. Claude searches the live web for the latest Baghdad restaurant news, new openings, phone numbers, and social media — then streams the answer back to you in real time, in your selected language.

---

## 🎨 Design System

- **Background**: Animated floating food emojis over a layered radial gradient scene with glowing orbs
- **Glass Effect**: `backdrop-filter: blur(18px)` with `rgba(255,255,255,0.10–0.20)` layers — exactly like iOS
- **Colors**: `#ff6b35` (accent), `#ffd60a` (gold), `#30d158` (green), `#5ac8fa` (teal)
- **Typography EN**: Syne (display) + DM Sans (body)  
- **Typography AR**: Noto Kufi Arabic (all text in Arabic mode)
- **RTL**: Full `dir="rtl"` switch with mirrored flex, borders, margins

---

## 🌐 GitHub Pages Deployment

The included workflow auto-deploys on every push to `main`:

1. Push to GitHub
2. Go to **Settings → Pages → Source: GitHub Actions**
3. Wait ~60 seconds
4. Your site is live at `https://YOUR-USERNAME.github.io/baghdad-bites`

---

## ⚠️ Disclaimer

Phone numbers shown are sourced from public records and may need verification. Baghdad Bites is a discovery and tracking tool — always call ahead to confirm details. This app scans publicly available data and uses AI to surface the latest information.

---

## 📄 License

MIT — free to use, fork, and build upon.

---

<div align="center">
  <strong>Baghdad Bites v3 © 2026 — بغداد بايتس</strong><br>
  Built with 🔥 for Baghdad's growing food scene
</div>
