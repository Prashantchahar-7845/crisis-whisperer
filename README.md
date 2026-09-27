# 🆘 Crisis Whisperer — Hyper-Local AI Rescue Navigation System

> **"The Last Mile Between a Rescue Boat and a Stranded Family."**  
> An emergency triage and navigation engine that bypasses traditional GPS during disasters by fusing community radio chatter, survivor photos, and local landmark descriptions into plain-language navigation directives.

---

## ⚡ The Problem: The "Last Mile" Breakdown

During floods, earthquakes, and humanitarian crises in rural, dense, or informal settlements:
- **GPS & Google Maps fail**: Water destroys road markers, cellular GPS drops, and 60% of rural terrain lacks mapped street names or house numbers.
- **Coordinates are useless to boat drivers**: Telling a volunteer rescue crew `28.6139° N, 77.2090° E` when water is 5 feet deep and roads are submerged does not help them locate a family.
- **Critical intel is scattered**: Crucial survivor reports are broadcast across WhatsApp groups, Telegram channels, and local radio in regional languages and dialects.

**Crisis Whisperer** solves this by converting non-coordinate survivor descriptions and visual cues into radio-style, turn-by-turn landmark directions (*"Go past the blue water tank, veer left before the temple, house with red door on your left"*).

---

## 🚀 Key Modules

| Module | Purpose | Unique Innovation |
|---|---|---|
| **🆘 Survivor Triage** | Calm natural dialogue with survivors | Triangulates survivor position from descriptions without asking for coordinates |
| **📸 Photo Analysis** | Computer vision for crisis photography | "GPS from Pixels" — extracts flood depth, landmarks, and structural cues even with stripped metadata |
| **📻 Community Intel Fusion** | Scrapes multi-lingual community chatter | Normalizes WhatsApp/Telegram/Radio reports in local dialects into structured danger maps |
| **🧭 Rescue Route Whisperer** | Radio-style turn-by-turn rescue directions | Plain-language directions with hazard alerts, water depth, and visual arrival signals |

---

## 🛠️ Getting Started Locally

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or newer)
- npm (comes with Node.js)

### Installation & Launch

1. **Clone or navigate to the project directory:**
   ```bash
   cd crisis-whisperer
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```
   *(or `npm start`)*

4. **Open in browser:**
   ```
   http://localhost:5173
   ```

---

## ⚙️ Modes: Simulation vs. Live Claude AI

Crisis Whisperer is designed to work **100% out of the box** without requiring any paid API keys:

- **Simulation Mode (Default)**: Automatically loaded with intelligent, realistic crisis scenarios. You can test triage chatting, photo uploads, intel fusion, and route generation immediately at zero cost.
- **Live Claude Mode**: Click the **⚙ Mode** button in the top-right header (or set `VITE_ANTHROPIC_API_KEY` in `.env.local`) to connect directly to Claude 3.5 Sonnet for real-time generative intelligence.

---

## 📦 Tech Stack

- **Framework**: [React 19](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Typography**: IBM Plex Mono & Space Grotesk (Tactical Emergency Theme)
- **Styling**: Vanilla CSS with hardware-accelerated animations and scanline overlays
- **AI Integration**: Anthropic Messages API (`claude-sonnet-4-20250514`) with autonomous fallback engine

---

## 📄 License
MIT License. Created for humanitarian crisis response and disaster relief hackathons.
