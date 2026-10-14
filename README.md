
# Volkswagen Passenger Cars India: Commercial Analytics Platform (FY2026)

An end-to-end Power BI business intelligence platform tracking commercial performance, variant mix, and regional sales dynamics across Volkswagen India's dealership network.

---

## Executive Overview
This 5-page analytical interface transforms transactional sales data into actionable commercial intelligence, covering:
* **Executive Diagnostics (Page 1):** Realized revenue, unit volumes, and high-level dealership velocity.
* **Model Dynamics & Ranking (Pages 2 & 3):** Time-series analysis across Virtus, Taigun, and Tiguan lines using Ribbon and Area visual flows.
* **Pricing Waterfall (Page 4):** Cost-component breakdown isolating ex-showroom pricing, statutory taxes (RTO/TCS), and on-road realizations.
* **Geographic Performance (Page 5):** Interactive map cross-filtering regional demand, branch-level volumes, and performance engine penetration.

---

## Technical Highlights

### 1. Data Transformation (Power Query / M)
* Engineered continuous fiscal calendar mapping using custom `Month_Index` logic (April–March).
* Standardized categorical string fields and enforced strict data typing to ensure seamless time-intelligence modeling.

### 2. DAX Measures & Modeling
Key metrics engineered for volume-weighted performance analysis:

### 3. Visual System & UX
* Styled to corporate design standards utilizing official Volkswagen brand palettes (VW Deep Navy `#001E50` and Ice Blue `#00B0F0`).
* Configured bidirectional cross-filtering between geographic map components, branch-level matrix tables, and dynamic KPI cards.

---

## Repository Artifacts
* `/reports/`: Contains the complete Power BI desktop file (`.pbix`).
* `/dax/`: Standalone `.dax` scripts containing all calculated columns and core measures.
* `/assets/`: High-resolution dashboard screenshots.

---

## How to Run Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)Nivas1707/vw-india-commercial-analytics-fy2026.git
   ```
2. Open `/reports/VW_India_Commercial_Analytics_FY2026.pbix` in **Power BI Desktop** (Windows).
3. If re-pointing to raw data sources, update the source path via **Power Query > Data Source Settings**.
