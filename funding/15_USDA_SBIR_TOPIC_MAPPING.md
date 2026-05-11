# USDA SBIR Topic Mapping — Levee Line Research LLC

_Adapted 2026-05-11 from prior AgTools grant strategy work. The granular USDA NIFA SBIR Topic 8.x analysis below was originally drafted for AgTools-as-applicant; reframed here for Levee Line Research LLC as the federally-funded R&D engine with AgTools as the commercialization vehicle._

Companion to `louisiana/10_LOUISIANA_GRANTS_STRATEGY.md` (which covers the broader federal-plus-state landscape) and `funding/14_RESEARCH_IMPACT.md` (which supplies the broader-impacts narrative).

---

## USDA NIFA SBIR — Why It's the Number-One Federal Fit

| Aspect | Details |
|--------|---------|
| **Agency** | USDA NIFA |
| **Phase I funding** | $175,000 (recent solicitations; verify in FY26/27 RFA when released) |
| **Phase II funding** | Up to $650,000 |
| **Duration** | 8 months (Phase I), 24 months (Phase II) |
| **Cost share** | None required |
| **Status (May 2026)** | Reauthorized through 2031 via S.3971 (signed April 13–14, 2026). FY26/27 Phase I RFA expected summer 2026. |
| **Why #1** | Levee Line / AgTools is a technology product with verified commercial potential — exactly what SBIR funds. Existing v6.17 production platform satisfies the commercialization-plan requirement out of the box. |

---

## Relevant Topic Areas (Detailed Mapping)

### Topic 8.2 — Plant Production and Protection (Biology)

**SBIR call language emphasizes:** Pest/disease identification systems, AI-based crop health monitoring, novel detection methodologies, decision-support tools for biological problems in row crops.

**Levee Line research scope that fits:**
- Multi-modal pest/disease detection combining UAV imagery, Sentinel-2 satellite, and ground sensor data
- Computer vision models trained on Delta-specific row-crop label sets (cotton, soybeans, corn, rice)
- Yield-gap prediction at field-level resolution
- Interpretability layer (SHAP, attention rollout) so end-users understand model outputs

**Existing AgTools deployment slot:**
- Pest & Disease ID module — 46+ species covered, hybrid cloud/local AI with HuggingFace, image + symptom Q&A, top-5 confidence scoring
- Crop Health Scoring module — NDVI and Excess-Green from imagery
- Yield Prediction module — Random Forest, 6 crops

**Why this combination is strong:** Most Topic 8.2 applicants propose to build a model. Levee Line proposes to research a *novel* model and deploy it into a platform that's already serving the workflow.

---

### Topic 8.3 — Plant Production and Protection (Engineering)

**SBIR call language emphasizes:** Precision agriculture technologies, variable-rate application, decision support systems, sensor integration.

**Levee Line research scope that fits:**
- Variable-rate decision algorithms using fused multi-modal sensor data
- Spray-mix optimization research (extending the existing JDOps analysis CLIs)
- Sensor-fusion methodologies for low-cost in-field deployment
- Equipment-data interpretation models leveraging JDOps OAuth integration

**Existing AgTools deployment slot:**
- Spray Recommendations module — 40+ products, MOA rotation, weather integration
- Standalone JD Operations Center CLIs — 5 scripts for spray-mix analysis, clustering, cost flagging, and optimization (`scripts/jd_ops/`)
- Equipment Tracking module
- Inventory Control module

---

### Topic 8.5 — Air, Water, and Soil

**SBIR call language emphasizes:** Environmental monitoring, input reduction technologies, sustainability quantification, conservation practice validation.

**Levee Line research scope that fits:**
- Carbon-flux modeling for Delta row-crop systems
- Soil-health prediction from sensor and satellite data
- Input-reduction decision algorithms validated against yield outcomes
- Conservation practice impact quantification

**Existing AgTools deployment slot:**
- Sustainability Metrics module — EPA/IPCC-compliant carbon accounting, 14 conservation practices, A–F sustainability grade, per-acre CO2e
- Climate & Weather module — GDD tracking, frost dates, heat stress
- Field Trial Tools — for conservation practice trials

**Why this is competitive:** The sustainability accounting in AgTools is already built to EPA/IPCC standards. Levee Line research can extend the validation methodology and quantify benefit at scale — exactly what reviewers want to see in Topic 8.5.

---

### Topic 8.9 — Small and Mid-Size Farms

**SBIR call language emphasizes:** Technologies that improve farm profitability, decision support tailored to smaller operations, accessibility, mobile-friendly tooling.

**Levee Line research scope that fits:**
- AI tools priced for sub-5,000-acre operations (commercial platforms target only large corporate farms at >$50K/year)
- Mobile-first deployment patterns for field use
- Validation that decision support actually changes outcomes for the small/mid-size cohort

**Existing AgTools deployment slot:**
- Mobile PWA interface (installable on phones/tablets without an app store)
- Planned $199/month SaaS pricing — explicitly targeting the small/mid-size segment
- Full feature set (pest ID, spray, accounting) accessible to operations that can't afford commercial precision-ag platforms

**Why Topic 8.9 is particularly strong:** Levee Line is *in* East Carroll Parish — a rural, economically distressed parish in the Delta Regional Authority service area. The broader-impacts narrative writes itself. Reviewers favor applications that bring innovation to underserved areas; this is the textbook case.

---

## Key Dates (Typical USDA NIFA SBIR Cycle)

| Phase | Typical Timing | Note |
|-------|---------------|------|
| Phase I RFA release | September (historical) | FY26/27 cycle delayed by post-lapse reauthorization — watch summer 2026 |
| Phase I deadline | January (historical) | Delayed in line with RFA release |
| Phase II deadline | September | For Phase I awardees only |

**Action:** Set Grants.gov alerts for "USDA NIFA SBIR" and check nifa.usda.gov/grants/programs/sbir-sttr monthly through summer 2026.

---

## Application Readiness — What's Already in Place

| Required Element | Status |
|------------------|--------|
| Technology with novelty | Levee Line research thesis: multi-modal yield-gap prediction with interpretability (see `research/09_AG_RESEARCH_SCOPE.md`) |
| Commercial potential | Verifiable via AgTools v6.17 production deployment, 830+ endpoints, JDOps OAuth integration |
| Team qualification | 30 years of row-crop operational experience + active commercial platform development (`AGTOOLS.md`) |
| Letters of support | Email drafts ready in `EMAIL_DRAFTS.md` for LSU AgCenter, UADA Rohwer, UAPB, growers |
| Data Management Plan | Boilerplate in `research/09_AG_RESEARCH_SCOPE.md`; full DMP summary in `funding/14_RESEARCH_IMPACT.md` |
| Research impact narrative | `funding/14_RESEARCH_IMPACT.md` |
| Commercialization plan substrate | `AGTOOLS.md` (the existing product anchors the Phase III story) |
| SAM.gov registration | Pending (started during Week 1 of formation; see `00_MASTER_CHECKLIST.md`) |
| Grants.gov registration | Pending (after SAM.gov is active) |
| EIN | Pending (Day 1 of formation; see `formation/03_EIN_APPLICATION.md`) |
| Operating Agreement | Drafted (`formation/02_OPERATING_AGREEMENT.md`) |
| Articles of Organization | Drafted (`formation/01_ARTICLES_OF_ORGANIZATION.md`) |

---

## Other Federal Pathways (Brief)

These are covered in more depth in `louisiana/10_LOUISIANA_GRANTS_STRATEGY.md`. Listed here for cross-reference:

| Program | Phase I Funding | Key Differentiator |
|---------|----------------|---------------------|
| **NSF SBIR (AI topic)** | up to ~$305K | Emphasizes technical innovation, broader societal impacts |
| **AFRI A1541 DSFAS** | up to $650K | Requires equal grounding in ag science AND data science (3–5 yr) — Levee Line's tightest fit |
| **AFRI A1531 / Foundational** | $300K–$650K | Adjacent fit |
| **AFRI SAS CAP grants** | $1M–$10M | Too large to prime; pursue as sub-awardee under LSU AgCenter |
| **NRCS CIG** | up to $2M Classic | Climate-smart partnership angle; LSU AgCenter has prior CIG funding |
| **DOE Office of Science SBIR** | $200K–$275K | Bioenergy intersection only |
| **NASA SBIR Appendix B** | $150K | Remote-sensing subtopic (INSTALG.5.S26B) due 2026-05-21 — tight |
| **FFAR (private foundation)** | varies | Bold food/ag research; private foundation pathway |
| **Southern SARE Producer Grant** | $10K–$30K | Farmer-led research; pairs with AgTools field-trial tools |
| **Louisiana On-Farm Grant (LSSAC)** | up to $50K across cycles | LA-specific, free technical assistance available |

---

## Next Actions

1. **Watch for FY26/27 NIFA SBIR RFA release** — expected summer 2026 after the SBIR/STTR reauthorization restart
2. **Pre-draft a Topic 8.2 or 8.9 Phase I proposal** during the lapse-window time
3. **Complete SAM.gov registration** as soon as EIN is in hand (post-LLC-formation)
4. **Send the LSU AgCenter, UADA Rohwer, and UAPB outreach emails** from `EMAIL_DRAFTS.md` now to start the relationship clock
5. **Engage Louisiana LTTO** for the $5,000 proposal-prep reimbursement — pays for a grant writer's polish layer on the Phase I draft
