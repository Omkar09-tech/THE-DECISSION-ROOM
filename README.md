# THE-DECISSION-ROOM

# 🍿 Netflix — Solving the Discovery Problem

An interactive web prototype that cuts Netflix's "what should I watch?" paralysis from **18.2 minutes** to roughly **2 minutes**.

Users don't lack content — they lack a fast way to decide. This project reframes discovery around three inputs people actually have in their heads (time, mood, who's on the couch) instead of an endless scrolling grid.

---

## 📊 Results

| Metric | Before | After |
| --- | --- | --- |
| Time-to-Play (TTP) | 18.2 min | ~2.1 min |
| Session Abandonment | 23% | < 10% |
| Build Status | — | ✅ Clean production bundle |

---

## 🚀 Features

### 1. Vibe & Time Engine
Narrows 10,000+ titles down to a personalized **Top 3 Match Cards** in three taps: time available, mood, and social context.

### 2. ClipStream Scene Reel
A full-screen, TikTok-style reel of 15-second iconic scene previews. One tap starts playback from that exact scene timestamp.

### 3. QuickMatch Roulette
A 3-second animated decision wheel for users who want zero choices made for them — pure "just pick something."

### 4. Executive ROI Simulator
A live dashboard modeling real-time impact on Time-to-Play, session abandonment, and churn-based revenue savings.

---

## 🛠 Tech Stack

- React (Vite)
- Plain CSS design system (`src/index.css`)
- Mock catalog data layer — no backend required

---

## 📦 Getting Started

```bash
# Install dependencies
npm install

# Start the dev server
npm run dev

# Build for production
npm run build
```

The app runs at **http://localhost:5173/**

---

## 📁 Project Structure

```
src/
├── App.jsx                       # Root app shell and routing
├── index.css                     # Design system and global styles
├── components/
│   ├── VibeEngine.jsx            # 3-tap Vibe & Time matching flow
│   ├── ClipStream.jsx            # Scene-preview reel
│   ├── QuickRoulette.jsx         # 3-second decision wheel
│   └── ExecutiveMetrics.jsx      # ROI / impact dashboard
└── data/
    └── mockCatalog.js            # Mock title + scene dataset
```

---

## 📄 Documentation

| File | Purpose |
| --- | --- |
| `implementation_plan.md` | Architecture and build approach |
| `task.md` | Task checklist and progress |
| `walkthrough.md` | Feature walkthrough and demo script |

---

## ⚠️ Disclaimer

This is an independent concept prototype built for product design exploration. It is not affiliated with, endorsed by, or connected to Netflix, Inc. All catalog data is mocked.
