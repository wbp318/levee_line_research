# AI Agriculture Research Scope — Levee Line Research LLC

Defining what Levee Line Research does, why it matters, and how it aligns with grant funding opportunities.

---

## Mission

Levee Line Research LLC develops artificial intelligence and machine learning solutions for agriculture, with a focus on the Mississippi Delta region. We build practical, accessible AI tools that help farmers make better decisions about planting, monitoring, and harvesting — starting with the crops and conditions of the lower Mississippi Valley.

---

## Research Focus Areas

### 1. AI Crop Monitoring and Disease Detection
**What:** Computer vision systems that analyze drone, satellite, and ground-level imagery to identify crop diseases, pest infestations, nutrient deficiencies, and water stress before they become visible to the naked eye.

**Why it matters:** Early detection can save 10-30% of crop yield. Small and mid-size farmers in the Delta lack access to expensive precision ag platforms.

**Grant alignment:**
- NSF SBIR AI2 (Computer Vision)
- USDA SBIR (Crop monitoring and disease detection)
- USDA AFRI (as university sub-awardee)

### 2. Yield Prediction Models
**What:** Machine learning models that predict crop yields using historical data, weather patterns, soil conditions, and satellite imagery. Helps farmers plan harvest logistics, storage, and sales.

**Why it matters:** Accurate yield prediction reduces waste, improves planning, and helps farmers negotiate better contracts.

**Grant alignment:**
- USDA SBIR (Yield prediction models)
- NSF SBIR AI6 (Sustainable AI for Low Resource Environments)

### 3. Precision Agriculture / Variable-Rate Application
**What:** AI-driven systems that optimize the application of seeds, fertilizer, herbicides, and water by varying rates across a field based on soil conditions, topography, and crop needs.

**Why it matters:** Reduces input costs by 15-25%, reduces chemical runoff, improves environmental outcomes. The Delta's rich alluvial soils have high variability that benefits from variable-rate approaches.

**Grant alignment:**
- USDA SBIR (Precision agriculture, variable-rate application)
- 2026 Farm Bill EQIP subsidies
- DOE SBIR (if tied to energy-efficient farming)

### 4. Remote Sensing and Drone Data Analysis
**What:** Processing and analyzing data from drones, satellites (Sentinel-2, Landsat, Planet), and ground-based sensors. Building AI pipelines that turn raw imagery into actionable field maps.

**Why it matters:** Remote sensing data is increasingly available but farmers lack tools to interpret it. Levee Line Research bridges the gap between raw data and farm decisions.

**Grant alignment:**
- USDA SBIR (Remote sensing, automated scouting)
- NSF SBIR AI2 (Computer Vision)

### 5. Climate-Resilient Farming Strategies
**What:** AI models that recommend crop rotations, planting dates, and variety selection based on climate projections and historical weather patterns. Helping Delta farmers adapt to changing conditions.

**Why it matters:** The Mississippi Delta faces increasing flood risk, heat stress, and shifting growing seasons. Data-driven adaptation strategies are essential.

**Grant alignment:**
- USDA AFRI Sustainable Agricultural Systems ($1M-$10M projects)
- Gates Foundation agricultural innovation
- NSF AI-ENGAGE (international collaboration on climate-resilient ag)

### 6. Soil Health Analytics
**What:** Machine learning models that analyze soil samples, satellite data, and field history to assess and predict soil health metrics (organic matter, compaction, drainage, nutrient levels).

**Why it matters:** Soil health is the foundation of productivity. The Delta's alluvial soils are highly productive but face compaction and drainage challenges.

**Grant alignment:**
- USDA SBIR (soil science topics)
- USDA NRCS conservation programs

---

## Regional Advantage: The Mississippi Delta

Levee Line Research is uniquely positioned in the Mississippi Delta — one of the most productive agricultural regions in the world. This location provides:

**Research advantages:**
- Direct access to large-scale row crop operations (cotton, soybeans, corn, rice)
- Proximity to diverse farming operations across Louisiana and Mississippi
- Real-world testing environment for AI tools
- Relationships with local farmers who need these solutions

**Grant competitiveness:**
- USDA and NSF prioritize rural and underserved communities
- East Carroll Parish qualifies as a rural, economically distressed area
- "Broader impacts" sections of grants are strengthened by serving Delta farmers
- Programs like USDA SBIR specifically want technologies that reach small/mid-size farmers

**Crops commonly grown in the region:**
- Soybeans
- Cotton
- Corn
- Rice
- Sweet potatoes
- Wheat
- Grain sorghum

---

## Technology Stack (Planned)

| Layer | Technology | Purpose |
|-------|-----------|---------|
| AI/ML Framework | PyTorch, TensorFlow | Model training and inference |
| Computer Vision | OpenCV, YOLO, Segment Anything | Image analysis and object detection |
| Geospatial | QGIS, Rasterio, GeoPandas | Satellite/drone data processing |
| Cloud | AWS / GCP | Model training, data storage, API hosting |
| Data Sources | Sentinel-2, Landsat, Planet, USDA NASS | Satellite imagery and agricultural data |
| LLM Integration | Claude API (Anthropic) | Natural language interface for farmers |
| Frontend | Web + mobile app | Farmer-facing dashboard and alerts |

---

## Competitive Landscape

| Competitor | Focus | Our Differentiation |
|-----------|-------|---------------------|
| Climate Corp (Bayer) | Large-scale precision ag | We focus on small/mid-size farms, lower cost |
| Farmers Edge | Data-driven decisions | We're Delta-specific, locally grounded |
| Taranis | Aerial crop intelligence | We use publicly available satellite data (lower cost) |
| aWhere | Weather analytics | We integrate weather with soil + imagery + AI |
| Granular (Corteva) | Farm management | We're research-first, grant-funded, not vendor-locked |

**Key differentiators:**
1. **Delta-focused** — built for the specific crops, soils, and conditions of the lower Mississippi Valley
2. **Accessible** — designed for farmers who can't afford $50K/year precision ag platforms
3. **Research-backed** — grant-funded R&D means we can invest in novel approaches
4. **Open data** — leverage publicly available satellite imagery and USDA datasets
5. **AI-native** — built from the ground up with modern AI, not legacy systems with AI bolted on

---

## Grant Proposal Talking Points

When writing SBIR/STTR proposals, emphasize:

1. **Technical Innovation:** Novel application of [computer vision / ML / LLMs] to [specific ag problem]. Not just applying existing tools — developing new approaches tailored to Delta agriculture.

2. **Commercial Potential:** 2+ million farms in the US. Precision ag market growing 12%+ annually. Subscription SaaS model for farmers at $20-50/month is commercially viable.

3. **Broader Impacts:** Serving rural, economically distressed communities in the Mississippi Delta. Reducing chemical runoff. Improving food security. Creating tech jobs in underserved areas.

4. **Team Qualifications:** Managing Member with agricultural background and AI/tech expertise. Located in the heart of the production region. Direct relationships with farming operations.

5. **Feasibility:** Using proven AI architectures (transformers, CNNs) applied to well-understood data sources (satellite imagery, weather data). Low technical risk, high impact potential.

---

## University Partnership Targets

Reach out to these institutions for AFRI collaborations and research partnerships:

| University | Department / Center | Why |
|-----------|-------------------|-----|
| LSU AgCenter | Precision Agriculture Lab | Louisiana land-grant, strong ag research |
| Southern University | Agricultural Research | HBCU land-grant, USDA partnerships |
| Mississippi State University | Geosystems Research Institute | Leading remote sensing + ag research |
| Alcorn State University | School of Agriculture | Received $1.15M AI talent grant, SW Mississippi |
| Jackson State University | AI/Data Science | Received $1.3M AI education grant |
| University of Arkansas | Division of Agriculture | Delta research station network |

---

## Year 1 Research Goals

1. **Q2 2026:** Build proof-of-concept crop disease detection model using Sentinel-2 imagery for soybean fields in East Carroll Parish
2. **Q3 2026:** Deploy drone-based field monitoring on 2-3 cooperating farms, collect training data
3. **Q4 2026:** Submit USDA SBIR Phase I proposal with preliminary results
4. **Q1 2027:** If NSF SBIR awarded, begin Phase I research program
5. **Q2 2027:** Present results at a regional ag conference (e.g., Beltwide Cotton Conference, Delta Farm Press events)

---

## Flagship A1541 DSFAS Project Concept

**Working title:** _Interpretable multi-modal yield-gap prediction for small-and-mid Mississippi Delta row-crop operations: fusing UAV thermal/multispectral, Sentinel-2/Landsat, and ground-sensor data with farmer-in-the-loop validation._

**Why this concept fits A1541 specifically:**
- **Equal grounding in ag science and data science.** Ag-science half: agronomic yield-gap analysis on Delta cotton/soy/corn across smallholder fields underserved by commercial precision-ag platforms. Data-science half: multi-modal sensor fusion + spatial-transformer architecture + post-hoc interpretability (SHAP, attention rollout).
- **Targets a real ag problem.** Yield gaps on small-and-mid Delta farms are documented but poorly explained at field-level resolution because commercial tools target large operations.
- **Defensible novelty.** Most public yield-prediction models use either satellite-only or sensor-only inputs; few fuse three modalities at <10 m resolution, and almost none ship with farmer-validated interpretability for non-technical end-users.
- **Has a commercialization pathway.** $20–$50/month SaaS targeted at the small-and-mid grower segment that Climate FieldView/Granular under-serve.
- **Has a clear "broader impacts" frame.** East Carroll Parish is rural and economically distressed; reaches underserved farmers who can't afford $50K/yr precision-ag platforms.

**Required ingredients to make this winnable:**
- LSU AgCenter co-PI or strong letter of support (Northeast Research Station, St. Joseph LA)
- 3–5 cooperating Delta growers with signed data-sharing agreements (start collecting now)
- Documented baseline against published methods (state of the art for satellite-only yield models)
- Pre-registered evaluation plan (test counties / test seasons held out)
- Data Management Plan compliant with NIFA FY2019+ requirements (see below)

---

## Data Management Plan Posture

NIFA has required a Data Management Plan on every competitive grant since FY2019. Levee Line's default DMP boilerplate should cover:

- **Data types collected:** UAV imagery (multispectral, thermal), satellite imagery (Sentinel-2, Landsat), soil moisture / temperature sensor logs, weather station data, yield monitor data from cooperator farms, hand-labeled ground-truth annotations.
- **Formats:** GeoTIFF for raster, COG-tiled for large archives, GeoParquet/CSV for tabular, JSON-LD for metadata. Imagery uses STAC catalog conventions.
- **Metadata standards:** STAC for imagery, USDA NAL DataONE conventions for tabular, ISO 19115 for geospatial.
- **Sharing/preservation:** Public-derived products (model weights, evaluation benchmarks) released to a public archive (Zenodo or AgDataCommons). Farmer-identifiable data and proprietary commercial inputs held privately under data-sharing agreements; aggregated derivatives publishable.
- **IP considerations:** Pre-existing IP (model architectures, algorithms) held by Levee Line. Grant-generated software released under permissive license (Apache 2.0 or MIT) where contractually permitted; commercial deployment proceeds under company terms.
- **Retention:** 7 years minimum per federal grant requirements; permanent for public derivatives.

---

## End-User Letters of Support — Strategy

Letters from end-users (farmers, co-ops, extension agents, ag-tech buyers) are the cheapest competitive differentiator on USDA grants. They are not formally required but reviewers weight them heavily.

**Target letter portfolio:**
- 3–5 individual Delta row-crop growers (East Carroll, West Carroll, Madison, Tensas parishes — plus 1–2 Chicot AR if working that side)
- 1–2 grower co-ops or producer associations
- 1–2 extension agents (LSU AgCenter, UAPB)
- 1 commercial ag-tech or input-supplier letter (Pivot Bio, Indigo, John Deere — frame as future commercial customer)

**Letter content should specify:**
- Why the problem matters to the signer
- What specific commitment they'll provide (field access, data sharing, in-kind labor, Phase III purchase commitment)
- Quantitative commitment where possible (acres available, growing seasons committed, dollar value of in-kind contribution)

Start collecting at least placeholder commitments **now**. Real letters take 4–6 weeks lead time. The October–December SBIR window will arrive too quickly to start cold.

---

## Activity Discipline — What to Avoid

The LLC's stated purpose is R&D in agriculture (NAICS 541715). Mixing unrelated activity into the same entity has real costs:

- **LA R&D Tax Credit risk:** QREs must align with the entity's stated research mission. Non-ag revenue dilutes the credit basis and triggers scrutiny.
- **Federal grant audit risk:** Grant funds and grant-funded researcher time must stay within the proposed scope. Co-mingled accounting on cross-business activity is an audit flag.
- **NAICS / SBA size-standard risk:** SBIR eligibility tests headcount and affiliation including all entities under common control. Off-topic side businesses get pulled into the math.

**The rule: revenue and activity outside ag-research go to a separate entity.** 318ecom LLC for e-commerce. A new entity for any other side ventures. Levee Line stays clean.
