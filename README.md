# AURA-D2C: Next-Generation Autonomous Advertising Intelligence & Decision Engine
> **DataQuest 3.0 Hackathon Entry**  
> *AI-Native Closed-Loop Cross-Platform Advertising Intelligence, Inventory Reconciliation & Real-Time Decision Directives*

---

## 🚀 Live Demo & Quickstart
The application is running live locally on **http://127.0.0.1:3000** (or port 3000).

```bash
# To run the development server:
npm run dev

# To build for production:
npm run build
```

---

## 🌟 Executive Problem & Solution Architecture

### The Problem in Modern D2C
D2C brand managers juggle fragmented ad networks (Meta Ads, Google Ads & PMax, Amazon Sponsored Products, TikTok for Business) alongside disconnected Shopify e-commerce data and ERP/3PL warehouse inventories. This causes:
1. **Attribution Double-Counting:** Google and Meta each claim credit for the same conversion, masking true blended ROAS and MER.
2. **Stockout Waste:** Ad algorithms continue bidding aggressively on products that have fewer than 3 days of stock, wasting capital on out-of-stock listings.
3. **Sub-optimal Arbitrage:** High-margin SKUs with high inventory sit idle on lower-converting channels while competitor stockouts on Amazon go unexploited.

### The AURA-D2C Solution
AURA-D2C bridges the gap between ad networks and unit-economics by establishing a **closed-loop autonomous intelligence loop**:
1. **Multi-Source Ingestion & Reconciliation:** Connects Meta, Google, Amazon, TikTok, Shopify, and NetSuite ERP. Normalizes currencies, reconciles click-level attribution, and eliminates duplicate conversions.
2. **SKU Margin & Inventory Context Join:** Joins unit landed COGS, gross margins, and inventory days-on-hand directly into bidding decision algorithms.
3. **Causal Reasoning Hub (The "Why"):** Identifies root-cause drivers (e.g. creative fatigue, frequency saturation, CPM surges) using Bayesian causal inference instead of passive correlations.
4. **Autonomous Decision Engine (The "Action"):** Formulates concrete closed-loop directives with confidence scores and predicted ROAS lifts, enabling single-click approval or guarded autopilot execution.

---

## 🔐 Enterprise Authentication Entry Portal (Pre-Dashboard Layer)
Before accessing the live intelligence command center, users are greeted by a high-converting, AI-native authentication portal:
- **Split-Screen Architecture:**
  - **Left Showcase:** Abstract cybernetic grid with an automated rotating **Value Proposition Carousel** highlighting Unified Intelligence, Autonomous Action Directives, Supply Chain Margin Protection, and Bayesian Causal Inference, backed by real-time platform trust indicators (SOC-2, GDPR, 256-bit API Vault).
  - **Right Form Portal:** Clean, accessible authentication form supporting smooth tab toggling between **Sign In** and **Create Account**.
- **Sign In Features:**
  - Work email & password input with interactive show/hide toggle.
  - "Remember me for 30 days" & interactive **Forgot Password modal** with client-side email format validation and simulated reset dispatch.
  - Social / Enterprise SSO options: **Continue with Google** and **Continue with Microsoft** with mandatory `prompt=select_account` to prevent silent auto-login and force account selection.
  - **⚡ 1-Click Instant Demo Access:** Pre-fills and authenticates as *Ashwin M. (D2C Growth Lead, Apex Athletics)* for rapid judge and reviewer evaluation.
- **Create Account Features:**
  - Full Name, Work Email, Company/Brand Name, and Password.
  - Dynamic **Password Strength Meter** (Weak, Fair, Good, Strong) with requirements validation (8+ chars, numbers, uppercase, special symbols).
  - Terms of Service & Data Processing agreement acceptance.
  - Social SSO registration via Google & Microsoft with `prompt=select_account`.
- **Seamless Session Management:**
  - Authenticated session smoothly opens the main dashboard and greets the user with an animated status notification.
  - User can click their profile avatar in the top navigation bar at any time to inspect their role or click **"Sign Out / Switch Account"** to return to the portal.

---

## 🖥️ Core Modules & Pages

### 1. Global Dashboard (Overview)
- **Unified KPI Cards:**
  - *Total Cross-Channel Spend:* $148,250 (+4.8% WoW)
  - *Blended ROAS (Omnichannel):* 3.82x (+0.34x / 9.8% lift)
  - *Attributed Revenue:* $566,315 (+14.2% lift)
  - *Avg Net Contribution Margin:* 28.4% (Post Ad Spend & COGS)
- **Cross-Platform Reconciled Visualization:**
  - Interactive multi-line & area chart built with Recharts.
  - Toggles between *Spend vs. Revenue*, *Channel Split*, and *Blended ROAS Trend*.
  - Channel performance pills with real-time ROAS and spend shares.
- **SKU Gross Margin & ERP Inventory Velocity Matrix:**
  - Direct integration of inventory metrics:
    - **SKU #104 (AeroVent Pro Runner):** 68.4% gross margin, 2,450 units in FBA (42 days supply), 4.82x Amazon ROAS vs 2.15x Google ROAS. Identified as high-yield arbitrage opportunity.
    - **SKU #208 (ThermoShield Merino Zip):** 42.1% gross margin, 180 units remaining (3.5 days supply). Identified as immediate stockout risk.
    - **SKU #312 (HydroFlow Flask):** 74.0% margin, 3,100 units buffer (60 days supply). Scale campaign candidate.

### 2. Autonomous Decision Engine (The "Action")
- **Closed-Loop Directives:**
  - `REC-101`: Reallocate $500/day from Google Generic Search to Amazon Sponsored Products for SKU #104.
  - `REC-102`: Throttle Meta Ads spend on SKU #208 by 60% immediately to prevent stockout ad waste.
  - `REC-103`: Scale TikTok 'Creator_Hook_04' Budget +$350/day into lookalike 2% audience.
  - `REC-104`: Apply negative keyword masking on PMax and redirect $400/day to high-margin category search.
- **Interactive Execution:**
  - `[Approve & Execute]` triggers simulated asynchronous API dispatch to ad network endpoints, updates live status to "Dispatched to Ad Platform", and records an entry into the audit trail.
  - `[Reject]` logs the dismissal reason for continuous reinforcement learning.
  - `[Rollback]` allows instant reversal of dispatched spend shifts.
  - `[Auto-Execute High Confidence]` applies all actions with &ge;92% confidence with a single click.
- **Autonomous Safety Guardrails:**
  - Modal configuring maximum daily reallocation caps ($1,500/day default), minimum ROAS floor target (3.2x), and stockout hard-stop safeguards.

### 3. Diagnostics & Reasoning Hub (The "Why")
- **Anomaly Detection Feed:**
  - Categorized timeline with severity levels (`Critical`, `Opportunity`, `Warning`).
  - Example: *Critical TikTok ad spend spike (+42%) with -18.4% conversion drop*.
  - Example: *Opportunity Meta campaign high conversion intent + ERP 1,200 units surplus inventory*.
  - Example: *Amazon Buy Box surged to 99.1% following competitor stockout on ASIN B09X872*.
- **Visual Causal Inference Graph:**
  - Decomposes anomalies along direct causal pathways:
    `[Creative Fatigue (4.6x Frequency)]` &rarr; `[Thumbstop Drop -38%]` &rarr; `[Auction CPM Surge +32%]` &rarr; `[PDP Bounce]` &rarr; `[ROAS Decay from 3.8x to 2.6x]`.
  - Displays Bayesian confidence intervals (96.4%) and one-click prescriptive mitigation.

### 4. Data Integration Map (The "Ingest & Reconcile")
- **Connected Data Sources Grid:**
  - Meta Ads Manager (Graph API v19.0 + Conversions API Gateway)
  - Google Ads & PMax (API v16 Enhanced Conversions)
  - Amazon Ads (SP-API / Advertising API v3)
  - TikTok For Business (Marketing API v1.3)
  - Shopify Plus Storefront (Admin GraphQL API & Webhooks)
  - NetSuite ERP / SAP Inventory (SuiteTalk REST API)
- **Live Mesh Telemetry:**
  - 99.85% cross-network match rate.
  - 1,420 unified SKU identifiers across Shopify, Amazon ASINs, and ERP barcodes.
  - Interactive `[Force Sync Mesh]` action demonstrating real-time ingestion.

### 5. Scenario Sandbox (What-If Budget Allocator)
- Interactive sliders for Meta, Google, Amazon, and TikTok spend.
- Dynamic marginal diminishing return curves modeling predicted blended ROAS and net contribution margin.
- `[Apply AI Optimal Split]` button demonstrating algorithmic multi-channel capital allocation.

---

## 🛠️ Technology Stack
- **Framework:** React 18 + Vite 6
- **Styling:** Tailwind CSS 3 with custom AI dark mode palette, glassmorphism, and glowing borders
- **Data Visualization:** Recharts ComposedChart, AreaChart, BarChart
- **Icons:** Lucide React
- **Typography:** Inter & JetBrains Mono (Google Fonts)
