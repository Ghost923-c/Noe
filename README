diff --git a/README.md b/README.md
index a1611f24d7729df7d32ed37d015c65e836cc6f77..ffd5bd74e50c00aeb629286e0de96417a6de09c5 100644
--- a/README.md
+++ b/README.md
@@ -1,43 +1,27 @@
-# AI Readiness Audit Toolkit
+# ENR Regulation, Compliance & Market Intelligence Monitor
 
-A lightweight browser app for law-firm technology and communications teams to run AI readiness audits for businesses.
+A lightweight browser prototype for an Energy & Natural Resources (ENR) monitoring device.
 
 ## What it does
 
-- Captures business and audit contact details.
-- Scores six AI readiness categories (1-5).
-- Includes extended South African financial-sector AI research questions (Q19-Q24).
-- Includes a multi-select checklist of generative AI value-chain use cases.
-- Displays visual graphs:
-  - Peer benchmark graph: AI adoption by sector in South African financial services
-  - Peer benchmark graph: intended AI investment bands (2024)
-  - Category score bar graph for each audit
-  - Maturity donut graph for each audit
-- Generates practical recommendations.
-- Lets you download audit files as JSON, CSV, and text report (`.txt`).
-
-## Logo setup
-
-Add the provided leopard logo image to this path:
-
-`assets/leopard-logo.png`
-
-The main banner loads the logo from that path.
-
-## Chart rendering
-
-- Peer benchmark charts use Chart.js via CDN in `index.html`.
-- If Chart.js is unavailable, the app falls back to canvas-drawn bars for the peer charts.
+- Tracks agential source connectivity against key news and database feeds.
+- Produces a compliance barometer for **Battery Manufacturing**.
+- Produces a compliance barometer for **Independent Power Producers (IPPs)**.
+- Produces a compliance barometer for **Wind & Solar Farms**.
+- Flags weak indicators (score <= 2) as priority intelligence actions.
+- Exports a timestamped JSON snapshot for downstream systems.
 
 ## Run locally
 
 ```bash
 python3 -m http.server 8000
 ```
 
-Then visit `http://localhost:8000`.
+Then open `http://localhost:8000`.
 
-## Where to add X
+## Configure modules and sources
 
-Open `app.js` and edit:
+Edit `app.js`:
 
+- `sourceFeeds` for the connected monitoring streams.
+- `modules` for each barometer and its scoring indicators.
