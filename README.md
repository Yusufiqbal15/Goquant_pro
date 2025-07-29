# Goquant_pro
This project is a Next.js + Three.js application that visualizes real-time cryptocurrency orderbook data in a fully interactive 3D environment, designed to provide deep insight into market dynamics, trading venue activity, and pressure zones.
Orderbook Depth 3D Visualizer – Real-Time Cryptocurrency Market Insight
This project is a Next.js + Three.js application that visualizes real-time cryptocurrency orderbook data in a fully interactive 3D environment, designed to provide deep insight into market dynamics, trading venue activity, and pressure zones.

📈 Core Features
3D Orderbook Graph
Rotating 3D bars represent orderbook depth over time with:

X-axis: Price

Y-axis: Quantity

Z-axis: Time
Smooth auto-rotation and manual controls for zoom, pan, and rotate.

Live Data Integration
Real-time WebSocket streams from free public APIs (e.g., Binance) for instant orderbook updates.
Smooth animation transitions without disrupting rotation.

Bid/Ask Visualization

Green bars: Bid orders

Red bars: Ask orders

Scalable price levels with cumulative volume depth rendering.

Venue Filtering System

Toggle between venues like Binance, OKX, Bybit, etc.

Unique color coding and legends for each venue.

Multi-select filters and dynamic updates.

Pressure Zone Detection

Detects high-volume clusters with visual heatmaps.

Volume spikes, order clustering, and spread analysis.

Alerts and stats panel for pressure insight.

Interactive Controls

Time range selection (1m, 5m, 15m, 1h)

Filters by venue, price range, quantity

Mode toggles: Real-Time, Historical, Pressure Zones

Search functionality for price levels and venues.

Advanced Visualization

Volume profile overlays

Order flow and trade matching animations

Spread analysis and bid/ask imbalance graph

Optional market depth heatmap

Performance & UX

Optimized for 60 FPS rendering

Mobile & tablet responsive with touch support

Level-of-detail rendering for large datasets

Dark/Light mode toggle

🛠️ Tech Stack
Framework: Next.js (React + TypeScript)

3D Engine: Three.js

Real-Time Data: Binance WebSocket API (or similar)

UI/UX: Tailwind CSS + Custom Controls

State Management: React Context + Custom Hooks

Testing: Jest (unit tests)

🚀 Getting Started
bash
Copy
Edit
git clone https://github.com/yourusername/orderbook-3d-visualizer
cd orderbook-3d-visualizer
npm install
npm run dev
ℹ️ See the README.md for full setup guide, API configuration, and developer notes.

📽️ Demo Video
A walkthrough video is provided in the submission, showcasing:

Feature highlights

Code architecture overview

Live data integration

Pressure zone logic

📄 Documentation
README.md – Setup, APIs used, architectural choices

components/ – Modular 3D and UI components

lib/ – WebSocket handlers, pressure zone detection logic

hooks/ – Custom hooks for real-time updates

tests/ – Unit tests for data and logic modules

✅ Status
✔️ Completed core functionality
🧪 Bonus features under development
⚙️ Fully working MVP
📱 Mobile optimized
🛠️ Ready for deployment and extension
