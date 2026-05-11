# agtools — Commercial Crop Consulting Product

A production-grade crop consulting system developed and maintained by William Brooks Parker. **Proprietary, commercially licensed only — source is not open.** Levee Line Research LLC operates as the federally-funded R&D engine; agtools is the commercialization vehicle.

---

## What It Is

agtools is a professional crop consulting platform covering:

- **Pest and disease identification** for row-crop systems
- **Spray recommendations** with mix-and-rate optimization
- **Economic analysis** of input decisions

The platform is built for the consultant, agronomist, and grower workflow — not a hobbyist tool. It's licensed commercially and is not available as open source.

---

## Maturity (as of May 2026)

| Metric | Value |
|--------|-------|
| Repository commits | 347+ |
| Current release | v6.17.0 |
| Major releases | 3 |
| Production-ready deployment | Yes (Docker-based) |
| CI/CD pipeline | Yes (GitHub Actions) |
| Contributors | William Brooks Parker (lead) + AI-assisted development |
| License | Proprietary — commercial licensing only |

This is not a prototype. It's a mature codebase with active development, semantic versioning, integration testing, and a containerized deployment path.

---

## Technical Architecture (Public Summary)

| Layer | Component |
|-------|-----------|
| Backend | Python service layer, containerized |
| Frontend | Web application |
| Database | Persistent relational store |
| Analytics | F# computational module |
| Mobile / R-optional | Mobile-friendly UX with optional R-based escalation path for advanced analysis |
| Integration | **John Deere Operations Center (JDOps)** — direct integration with the dominant equipment-data platform in row-crop agriculture |
| Deployment | Docker, environment-configurable, CI-tested |

The **JDOps integration is the strategic differentiator** — pulling field data directly from John Deere equipment is the kind of access most ag-tech startups spend years trying to build. agtools already has it.

---

## How agtools Relates to Levee Line Research LLC

| Entity | Role |
|--------|------|
| **Levee Line Research LLC** | Federally-funded R&D engine. Conducts the novel AI/ML research that produces new algorithms, models, and validated methodologies. Owns the research IP. |
| **agtools** | Commercial product. Deploys validated research into a consultant-and-grower-facing tool. The licensing and revenue vehicle. |

This separation is intentional and important:

1. **It satisfies SBIR/STTR commercialization-plan requirements.** SBIR reviewers want to see a credible path from research output to commercial deployment. "We will build something" is weak. "We already operate a v6.17 production product with a $X market — research output drops directly into the deployment pipeline" is exceptionally strong.

2. **It keeps grant funds clean.** Federal grant work is conducted at Levee Line; commercial deployment is conducted at agtools. Grant-funded R&D outputs are licensed (or otherwise transferred) to agtools under documented IP arrangements. No co-mingling of grant funds with commercial revenue.

3. **It protects each entity's specialization.** Levee Line stays a clean NAICS 541715 research entity — exactly what reviewers expect of a Phase I SBIR awardee. agtools handles the messy commercial reality (customer support, billing, ongoing maintenance, integrations).

---

## Why This Strengthens Grant Applications

A Phase I SBIR proposal asks: "If your research succeeds, how will it reach end users?"

Most applicants answer with hypotheticals. Levee Line answers with a working product:

- **Commercialization Plan section:** "Research output flows directly into agtools (v6.17, production), which already serves the consultant workflow agtools was built for. JDOps integration provides the data backbone. Phase III commercialization is operational, not theoretical."
- **Letters of Support:** End-user farmers and consultants who already use or evaluate agtools become natural letter-of-support signatories for Levee Line grant applications.
- **Management Team narrative:** "Principal Investigator has built and operates a v6.17 commercial crop consulting platform with 347+ commits and an active development cadence" — that's a capability claim grant reviewers can verify rather than take on faith.

---

## Access & Licensing

| Audience | Access Path |
|----------|-------------|
| **General public** | Information at this page only. Source is not available. |
| **Federal grant reviewers** | Read access to the private repository can be granted on request, time-limited for the review period. Contact via email at the address in `README.md`. |
| **University partners (LSU AgCenter, UADA, UAPB)** | Read access available under NDA for collaboration-scoping discussions. |
| **Prospective investors / advisors** | Read access available under NDA. |
| **Commercial licensees** | Contact via email for licensing terms. |

The repository itself is at `github.com/wbp318/agtools` (private). All access requests are evaluated case-by-case.

---

## Screenshots and Demos

_To be added — placeholder section. Recommended additions:_

- A screenshot of the spray-mix recommendation interface
- A screenshot of the pest/disease identification flow
- A screenshot of the economic analysis output
- A short (60–90 second) screencast demonstrating the consultant workflow end-to-end
- An architecture diagram (one image showing the layers and JDOps integration)

For grant proposals, an architecture diagram and 2–3 representative screenshots are usually sufficient. A screencast adds significant lift for investor / advisor conversations.

---

## Status Notes (May 2026)

- **v6.17.0 Backend polish, JDOps integration, mobile R-optional escalation path** — most recent major release (~4 days prior to this document's writing)
- **Active development** — commits within the past week
- **Recent feature work:** JDOps integration deepening, spray-mix analysis toolset, mobile workflow refinement, R-optional advanced-analysis escalation path
- **CI/CD healthy:** GitHub Actions running smoke tests on commits to master
