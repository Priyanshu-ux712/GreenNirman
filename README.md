## 🏗️ What Is GreenNirman?
 
GreenNirman is a **district-level green building assessment platform** built specifically for India's construction sector. It helps architects, civil engineers, urban local bodies, housing developers, and homeowners evaluate how sustainable their building design is — before a single brick is laid.
 
The user selects their district, enters building details, picks materials across 5 categories, and the platform instantly:
- Calculates a **sustainability score out of 100** with a letter grade (A+ to E)
- Estimates a **GRIHA star rating** (1–5 stars)
- Runs a **10-point ECBC 2017 compliance check** with pass/fail per parameter
- Computes **25-year lifecycle costs and energy savings**
- Generates a **professional 8-page PDF assessment report** — downloadable directly in the browser
 
All calculations happen **client-side in real time**. No project data is stored or transmitted anywhere.
 
---
 
## 📊 Platform Stats
 
| Metric | Value |
|---|---|
| Districts covered | 758 — all 36 states and UTs |
| Building materials | 72 across 5 categories |
| Result analysis tabs | 17 |
| Compliance standards | 24 Indian + international |
| Input fields | 24 |
| PDF report pages | 8 |
| Climate data coverage | 670 districts — NASA POWER 21-year averages (2000–2020) |
| Offline capable | ✅ Yes — works without internet after first load |
| URL sharing | ✅ Yes — all inputs encoded into a shareable link |
| Data privacy | ✅ Zero data collection — 100% local computation |
 
---
 
## ❓ Why It Was Built
 
India's building sector consumes **40% of national energy** and contributes **22% of total CO₂ emissions**. Over 9.2 million new buildings are constructed every year — projected to reach 11.3 million by 2028. The decisions made at design stage lock in a building's energy consumption for the next 50 years.
 
Yet existing green building assessment tools are designed for large metro projects and require expensive specialist consultants costing ₹50,000–5,00,000 per assessment. They cover roughly 50 cities. A builder in Varanasi, Sikar, or Imphal has had no access to affordable, district-specific guidance — until GreenNirman.
 
| The Gap | What GreenNirman Does |
|---|---|
| Existing tools cost ₹50,000–5,00,000/assessment | Assessment engagement model — accessible pricing |
| Only covers ~50 metro cities | Covers all 758 Indian districts |
| No accessible ECBC compliance tool | Automated 10-point ECBC 2017 check — instant Pass/Fail |
| No district-specific climate data | NASA POWER 21-year averages per district |
| No embodied carbon data for Indian materials | ICE Database v3 values for 72 Indian materials |
| No tool for EWS/LIG/PMAY builders | Affordable budget tier built specifically for them |
| Data stored on cloud | Zero data collection — runs entirely in browser |
 
---
 
## 👥 Who It Serves
 
- **Architects & Civil Engineers** — instant ECBC/GRIHA compliance check during design
- **Urban Local Bodies / Municipalities** — standardised assessment for green building approvals
- **Housing Boards & Developers** — material comparison with cost and carbon data
- **Individual Homeowners** — understand energy savings and water risk before building
- **EWS / LIG / PMAY Beneficiaries** — affordable-tier guidance with subsidy path information
- **Research & Academia** — open climate and material dataset for all 758 districts
 
---
 
## 🔢 How It Works — 3 Steps
 
### Step 1 — Location & Building Details
 
The user types a district name — a live typeahead searches across all 758 districts. Selecting a district automatically assigns the ECBC climate zone (1–5) and loads all district-specific data.
 
| Input | Range | Purpose |
|---|---|---|
| District Search | 758 districts | Sets climate zone, loads district data |
| Built-up Area | 10–2,00,000 m² | All area-based calculations |
| Number of Floors | 1–40 | Foundation carbon, seismic check |
| Building Type | Residential / Commercial / School / Hospital / Affordable (EWS/LIG) | Tariff, water norms, occupancy hours |
| Budget Category | Affordable / Standard / Premium / Luxury | Filters materials shown |
| Occupants | 1–5,000 | Water demand, DHW energy |
| WWR — 4 faces (N/S/E/W) | 5%–60% each | OTTV, ENS RETV, thermal score |
| Orientation | N / S / E / W / Composite | OTTV solar factor adjustment |
| Structural System | RCC Frame / Loadbearing / Steel / Timber+Bamboo | Foundation embodied carbon |
| HVAC System | Split AC / VRF / Chiller / Natural Ventilation | Cooling energy savings |
| Rainwater Harvesting | Toggle | Water score, GRIHA points |
| Solar PV | Toggle | Solar kWh, carbon credits at ₹1,500/tCO₂ |
| Night Cooling | Toggle | 12% cooling energy saving |
| Skylights / Light Shelf | Toggle | Daylighting, lighting energy reduction |
| C&D Waste Plan | Toggle | Biodiversity score |
| Low-VOC Materials | Toggle | IAQ score improvement |
| Permeable Surface | 0%–80% slider | Stormwater, heat island |
| Trees on Site | 0–50 slider | 21.77 kg CO₂/tree/yr sequestration (IPCC AR5) |
| Green Roof Coverage | 0%–100% slider | Biodiversity, insulation |
| Compare Mode | Toggle | Enables Scenario A vs B comparison |
 
### Step 2 — Material Selection
 
The user picks one material per category from a filtered list. Materials above their selected budget tier are automatically hidden. A search box lets them filter by name across all 72 materials.
 
Each material card shows: cost per m², carbon rating (A+ to E), embodied carbon (kg CO₂/kg), thermal conductivity (W/mK), lifespan (years), renewable/recycled badges, and climate zone suitability.
 
| Category | Count | Materials |
|---|---|---|
| Wall | 22 | Burnt Clay Brick, Fly Ash Brick, AAC Block, Stabilised Mud Block, Hollow Concrete Block, Rat-Trap Bond Brick, Adobe/Mud Wall, Stone Rubble Masonry, Laterite Stone Block, Fal-G/Geopolymer Block, Dhajji Wall, Rammed Earth Wall, Recycled/Salvage Brick, Bamboo Frame+Mud Plaster, Hempcrete Block, CSEB, Recycled Concrete Block, Cavity Brick Wall (2 variants), Autoclaved Siporex Block, Ferro-Cement Panel, Bamboo Frame+Plaster |
| Roof | 15 | RCC Flat Slab, Mangalore Clay Tile, Jack Arch Brick, GI Corrugated Sheet, Precast RCC Plank+Joist, RCC+Cool Roof Coating, Bamboo Roofing, Ferro-Cement Thin Shell, LECA Lightweight Clay, Terracotta Filler Slab, Green/Inverted Planter Roof, Thatch Roof, Polycarbonate Sheet, RCC Waffle Slab |
| Floor | 14 | Kota Stone, IPS Floor, Ceramic Tile, Shahabad Limestone, CEB Floor Finish, Bamboo Strip, Polished Concrete, Recycled Glass Mosaic, Cow Dung+Lime Polish, Terracotta Tile, Vitrified Tile, Marble, Granite, Athangudi Tile |
| Window | 8 | Single Glazed Al, Double Glazed uPVC, Single Glazed+Chajja, Double Glazed Al, Wooden Frame Single Glazed, Triple Glazed uPVC, Bamboo Slatted Screen+Glass, Polycarbonate Sheet |
| Insulation | 13 | EPS Thermocol, Rock Wool, Jute Fibre Batts, Coconut Coir Board, Rice Husk Ash Board, Perlite/Vermiculite, Foil Bubble Wrap, Hemp Wool Batts, Cellulose (Recycled Paper), Glass Wool, XPS Polystyrene, Aerogel Blanket, Recycled Denim |
 
### Step 3 — Review & Calculate
 
A summary of all selections is shown before calculating. The user confirms and clicks Calculate. All calculations run instantly in the browser and results appear across 17 tabs.
 
---
 
## 📈 Scoring System
 
The overall sustainability score (0–100) is a weighted sum of 7 independently calculated parameters:
 
| Parameter | Weight | What It Measures |
|---|---|---|
| Embodied Carbon | 30% | CO₂ locked into materials vs zone baseline (ICE v3) |
| Thermal Performance | 25% | U-value compliance + OTTV vs baseline + per-face WWR + orientation + SHGC pass/fail |
| Local Availability | 15% | How locally sourced the selected materials are — reduces transport carbon |
| Cost Efficiency | 10% | Material cost vs zone baseline (CPWD DSR 2024) |
| Durability | 10% | Average lifespan of selected materials vs 25-year benchmark |
| Renewable / Recycled | 5% | Fraction of materials that are renewable (bamboo, hemp) or recycled content |
| Water Efficiency | 5% | Rainwater harvesting toggle + penalty for high water-absorbing materials |
 
**Grade scale:** A+ (90–100) · A (80–89) · B (70–79) · C (60–69) · D (50–59) · E (below 50)
 
### GRIHA Star Rating
 
| Stars | Score Range | What It Means |
|---|---|---|
| ★★★★★ 5 Stars | ≥20 pts | Net-zero / LEED Platinum level |
| ★★★★ 4 Stars | 16–19 pts | ECBC 3-star / GRIHA 4-star range |
| ★★★ 3 Stars | 12–15 pts | GRIHA 3-star / ECBC compliant |
| ★★ 2 Stars | 8–11 pts | Meets minimum GRIHA 2-star |
| ★ 1 Star | Below 8 pts | Below minimum green rating |
 
*The GRIHA star estimate is a proxy for preliminary design guidance — not a substitute for formal GRIHA certification.*
 
---
 
## 📋 17 Result Analysis Tabs
 
| Tab | What It Shows |
|---|---|
| Scores | Total score, letter grade, GRIHA stars, EUI (kWh/m²/yr), peak cooling load, AC tonnage, CO₂ saved, tree equivalents, property value premium, CO₂ payback period |
| Recommendations | Priority-tagged (High / Medium / Low) recommendations based on district data, climate zone, materials, building type, and budget tier |
| Radar | Spider/web chart — your building vs conventional baseline across all 7 score dimensions |
| Carbon | Component-by-component embodied carbon: wall, roof, floor, plaster, foundation, frame, partition. Biogenic carbon stored (bamboo/hemp/timber). Tree equivalents bar chart. |
| Energy | Cooling, heating, infiltration, lighting, DHW savings. Monthly energy profile (12 months). Annual bill saving (₹/yr). 25-year energy NPV. HVAC system comparison. |
| ECBC | 10 compliance checks — actual value, zone limit, Pass/Fail: Wall U-value, Roof U-value, Window U-value, SHGC, OTTV, RTTV, SRI, WWR, ENS RETV, Seismic Risk |
| LCA | Full 25-year investment vs savings: material premium/saving, RWH cost, solar PV cost (post-subsidy), HVAC savings, energy NPV, maintenance, property premium, carbon credits — each with source citation |
| Label | A+ to E energy label with your building's grade highlighted on the visual scale |
| Compare | Side-by-side: Scenario A vs Scenario B — all scores, EC totals, energy savings, costs (visible when Compare Mode is ON) |
| Alts | Top 2 better material alternatives per category — EC delta, U-value delta, cost delta, and reason why it's better for your specific district and zone |
| District | Local data: seismic zone, flood risk, soil type, water scarcity, construction cost, government schemes, monthly climate chart from NASA POWER |
| Method | All formulas, calculation methods, and data sources — ISO 6946 U-value, ECBC OTTV, ENS RETV, ICE v3, NPV, CEA grid factor — with exact clause references |
| Benchmark | Your design vs 5 real GRIHA-certified Indian buildings: CII Sohrabji Godrej Green Business Centre (5★), Indira Paryavaran Bhawan (5★), IIT Delhi Academic Complex (4★), Suzlon One Earth Campus (5★), CEPT University Block 5 (4★) |
| IAQ | IAQ score: VOC status, daylighting, ASHRAE 55 thermal comfort, ventilation adequacy, fire rating, STC sound rating, daylight kWh saved |
| Passive | Passive design score: night cooling, skylights, north-biased orientation, low west WWR. Zone-specific strategies, monsoon waterproofing, shading depth guidance, thermal mass advice. |
| Bio | Biodiversity score: trees planted, green roof %, permeable surface %, stormwater runoff reduction, construction waste plan, urban heat island contribution |
| Summary | Complete project summary: overall grade, score, GRIHA stars, zone, CO₂ saved, tree equivalent, all 5 selected materials in a full properties table |
 
---
 
## 🏛️ ECBC 2017 Compliance Engine
 
10 automated compliance checks — each shows actual value, zone-specific limit, and Pass/Fail:
 
| Check | Standard | Limit |
|---|---|---|
| Wall U-value | ECBC 2017 Table 5-1 | 0.30–0.44 W/m²K by zone |
| Roof U-value | ECBC 2017 Table 5-1 | 0.20–0.33 W/m²K by zone |
| Window U-value | ECBC 2017 Table 5-1 | 0.80–5.80 W/m²K by material |
| SHGC | ECBC 2017 Table 5-4 | ≤0.25–0.51 by zone |
| OTTV | ECBC 2017 Section 5.3 | ≤45 W/m² (Zones 1–4) |
| RTTV | ECBC 2017 Section 5.3 | ≤25 W/m² (Zones 1–4) |
| SRI (roof) | ECBC 2017 Section 5.3.2 | SRI ≥ 78 |
| WWR limit | ECBC 2017 Section 5.2.2 | ≤40% of wall area |
| ENS RETV | Eco Niwas Samhita 2021 | ≤15 W/m² (residential) |
| Seismic Risk | IS 1893:2016 + IS 4326:2013 | G+2 max — unreinforced masonry in Zones IV–V |
 
---
 
## 📄 8-Page PDF Assessment Report
 
Generated entirely in-browser via jsPDF. Downloads as a real `.pdf` file. Can be submitted to urban local bodies, development authorities, banks, and government scheme applications.
 
| Page | Contents |
|---|---|
| 1 | Cover + Score: grade badge, GRIHA stars, all project details |
| 2 | Embodied Carbon: component breakdown, biogenic carbon, payback, tree equivalents |
| 2 | Thermal + ECBC: U-values with thermal bridging, SHGC, OTTV, RTTV, ENS RETV |
| 3 | Energy Performance: savings by category, monthly bar chart, EUI, AC tons, bill savings |
| 3 | Material Decisions: all 5 materials with U-value, EC, lifespan, ECBC badge |
| 4 | 25-Year LCA: full investment vs savings table with NPV and source citations |
| 4 | GRIHA Estimate: points by criteria with improvement guidance |
| 5 | Energy Label: A+ to E visual scale with your grade highlighted |
| 5 | Smart Alternatives + GRIHA Benchmark comparison |
| 6 | Water Demand: daily/annual demand, RWH coverage days |
| 7 | District Climate: HDD, CDD, monthly temperatures from NASA POWER |
| 7 | District Insights: seismic, flood risk, soil type, water scarcity, local materials |
| 8 | Recommendations: all priority-tagged with impact and action steps |
| 8 | Passive Design: zone-specific strategies, native trees, monsoon detailing |
| 9 | Methodology: all formulas, standards, data sources |
 
---
 
## 💰 Budget-Aware Material Filtering
 
| Tier | Cost Range | Max Material Cost | Target User | GRIHA Target |
|---|---|---|---|---|
| Affordable | ₹1,200–1,900/sqft | ≤ ₹2,499/m² | EWS/LIG, PMAY beneficiaries | 2 stars |
| Standard | ₹1,900–2,500/sqft | ≤ ₹4,999/m² | Mid-segment residential | 3 stars |
| Premium | ₹2,500–4,000/sqft | ≤ ₹8,999/m² | High-end residential | 4 stars |
| Luxury | ₹4,000+/sqft | All materials | Premium / green-rated commercial | 5 stars |
 
Each budget tier gets specific financial recommendations — Affordable users see the PMAY subsidy path (₹1.5–2.67 lakh), while Luxury users see the net-zero roadmap with GRIHA 5★ + LEED Platinum guidance.
 
---
 
## 🌍 Data Coverage
 
### Climate Zones (ECBC 2017)
 
| Zone | Name | Character | Example Districts | ~Districts |
|---|---|---|---|---|
| 1 | Hot & Dry | High heat, low humidity, desert/semi-arid | Jaipur, Jodhpur, Jaisalmer, Nagpur | ~180 |
| 2 | Warm & Humid | High humidity, coastal, moderate-high temp | Mumbai, Chennai, Kochi, Visakhapatnam | ~140 |
| 3 | Composite | Hot summer + mild winter — dual season | Delhi, Lucknow, Pune, Bengaluru, Bhopal | ~250 |
| 4 | Temperate | Moderate — long natural ventilation season | Mysuru, Coimbatore, Shillong, Darjeeling | ~80 |
| 5 | Cold | Cold winters, snow, high altitude | Leh, Srinagar, Shimla, Dehradun | ~108 |
 
### District Data
 
| Dataset | Districts | Source |
|---|---|---|
| DISTRICT_ZONE (climate zones) | 758 | ECBC 2017 zone map |
| DISTRICT_INSIGHTS (local data) | 758 | BIS IS 1893, NDMA, CGWB, NBSS, CPWD DSR 2024 |
| DISTRICT_CLIMATE_DB (NASA data) | 670 | NASA POWER 21-year averages (2000–2020) |
| Zone fallback (remote districts) | 88 | ECBC 2017 zone-level averages |
 
All 758 districts are real, unique, canonical entries — no duplicates or alternate names. The 88 districts without individual NASA data are mostly very small or remote districts in Northeast India and island territories.
 
---
 
## 📐 Standards & Data Sources
 
All calculations are based on 24 verified Indian and international engineering standards:
 
| Standard | Application |
|---|---|
| ECBC 2017 — BEE, Govt. of India | U-value limits, OTTV/RTTV formula, SHGC by zone, SRI ≥ 78, WWR ≤ 40% |
| Eco Niwas Samhita 2021 — BEE | RETV formula, ≤15 W/m² for residential buildings |
| IS 1893:2016 — BIS | Seismic zone classification for all 758 districts |
| IS 4326:2013 — BIS | Max floors for unreinforced masonry in seismic zones |
| IS 1172:2011 — BIS | Water demand norms by building type |
| IS 3646 + BEE LPD Norms | Lighting power density for energy calculation |
| NBC 2016 Part 8 — BIS | Occupancy hours by building type, passive design |
| ISO 6946:2017 | U-value calculation — Rsi 0.13 (walls), 0.10 (roofs) |
| ISO 14683:2017 | Thermal bridging ΔU correction |
| ISO 10456:2007 | Moisture correction for hygroscopic materials |
| ISO 13790:2008 | Monthly heating energy calculation |
| ISO 21930:2017 | Biogenic vs fossil carbon tracked separately |
| ASHRAE 62.1 | Infiltration ACH ranges by building type |
| ASHRAE 55 | Adaptive thermal comfort — setpoint reference |
| RICS WLCA 2017 | Foundation embodied carbon by structural system |
| ICE Database v3 — Circular Ecology, UK | Embodied carbon for all 72 materials |
| CEA CO₂ Baseline DB v20 — FY2023-24 | Grid emission factor: 0.727 kg CO₂/kWh |
| CERC / DISCOM 2024 | Electricity tariffs by building type (₹5.5–10/kWh) |
| CPWD DSR 2024 | Material costs and maintenance norms |
| RICS India 2022 / JLL India | 8% property value premium for green-rated buildings |
| IPCC AR5 | Tree CO₂ sequestration: 21.77 kg/tree/yr |
| NASA POWER API (NASA Langley) | 21-year monthly climate averages for 670 districts |
| NDMA National Flood Risk Atlas | District flood risk — Low / Moderate / High |
| CGWB Groundwater Year Book 2022-23 | Water scarcity level by district |
 
---
 
## 🛠️ Tech Stack
 
| Layer | Technology |
|---|---|
| Framework | React 18 — single-file component architecture |
| PDF Generation | jsPDF 2.5.1 — loaded from CDN, runs entirely in-browser |
| Deployment | Netlify |
| Climate Data | NASA POWER — embedded 21-year averages for 670 districts |
| Calculations | Pure JavaScript — no backend, no database, no API calls at runtime |
 
---
 
## ⚠️ Known Limitations
 
These limitations are documented openly in the app's Methodology tab:
 
- Wall area calculation assumes a square floor plan — irregular or L-shaped buildings may have ±10–15% OTTV variance
- 88 remote/small districts use zone-average climate data — slightly less precise for those districts only
- Building bylaws (FAR, setbacks, ground coverage) not populated for most districts outside major cities
- Structural frame carbon is estimated by system type, not calculated from actual structural drawings
- SHGC values are estimated from glazing type — manufacturer test certificate needed for formal GRIHA submission
- No MEP systems carbon (plumbing, electrical distribution) — underestimates total embodied carbon by ~10–15%
- GRIHA star estimate is a proxy only — not a substitute for formal GRIHA certification
- No BIM integration — all inputs are manual entry
- No multi-language support yet
 
---
 
## 🗺️ Roadmap
 
| Priority | Feature |
|---|---|
| 🔴 High | Hindi material names (72 materials) — for site engineers and local contractors |
| 🔴 High | Payment integration for premium report features |
| 🟡 Medium | "Show better option" instant swap button per material card |
| 🟡 Medium | Building bylaws database for remaining districts (FAR, ground coverage, setbacks) |
| 🟡 Medium | Nearby suppliers database — cement plants, quarries, fly ash sources per district |
| 🟢 Low | Multi-language support — Hindi / Tamil / Telugu |
| 🟢 Low | WCAG 2.1 AA accessibility — screen reader support, ARIA labels |
| 🟢 Low | Carbon credit marketplace link — India PAT scheme / REC registry |
 
---
 
## 👨‍💻 About the Developer
 
**Priyanshu Kumar**
B.Tech Computer Science & Engineering
Global Institute of Technology and Management, affiliated to Gurugram University, Haryana
 
🐙 [github.com/Priyanshu-ux712](https://github.com/Priyanshu-ux712)
💼 [linkedin.com/in/priyanshu-kumar-846b39320](https://www.linkedin.com/in/priyanshu-kumar-846b39320)
📧 priyanshukumar9053@gmail.com
 
*Built independently as a student project — no institutional funding, no team.*
 
---
 
## 🔒 Data Privacy
 
GreenNirman collects **zero user data**. All assessments run locally in the browser. No project data is stored, transmitted, or shared with any server at any point.
 
---
 
*GreenNirman — India's Green Building Assessment Platform | March 2026 | 🇮🇳 Made in India*
 
