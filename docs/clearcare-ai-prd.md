# ClearCare AI — Product Requirements Document (PRD)

## Objective
Reduce drug prices, lower insurance premiums, hold insurers accountable, and enforce price transparency using federal-grade AI.

## Policy Alignment
- Most-favored-nation pricing
- OTC expansion
- Subsidy redirection
- PBM kickback elimination
- Plain-English insurance
- Mandatory price disclosure (Medicare/Medicaid)

---

## 1. Product Overview
ClearCare AI is a federal AI platform that audits, enforces, and explains healthcare pricing and insurance behavior in real time for regulators and citizens.

**Primary users**
- HHS
- CMS
- CBO
- DOJ Antitrust
- State insurance commissioners
- Consumers

---

## 2. Core Modules

### A. Drug Price Intelligence (DPI-AI)
**Purpose**: Enforce global benchmark pricing and detect manufacturer/PBM violations.

**Capabilities**
- Ingests global drug price data (OECD, WHO, EMA).
- Enforces most-favored-nation benchmarks.
- Flags violations by manufacturers and PBMs.
- Simulates OTC eligibility impact on prices.

**Outputs**
- Violation alerts
- Price caps
- Savings forecasts

### B. PBM & Insurer Kickback Detection (KDA-AI)
**Purpose**: Detect non-transparent rebate routing and quantify premium inflation.

**Capabilities**
- Graph AI on claims, rebates, formularies.
- Detects non-transparent rebate routing.
- Estimates premium inflation due to kickbacks.

**Outputs**
- PBM risk scores
- Enforcement-ready audit trails

### C. Plain English Insurance Translator (PEIT)
**Purpose**: Convert complex policies into legally accurate, consumer-friendly summaries.

**Capabilities**
- LLM converts policies into legally accurate plain English.
- Highlights denial rates, wait times, payout ratios.
- Multilingual, accessibility-first.

**Outputs**
- Consumer-ready summaries
- Compliance reports

### D. Premium Reduction Simulator (PRS-AI)
**Purpose**: Model premium impacts from subsidy redirection.

**Capabilities**
- Models subsidy redirection directly to citizens.
- Estimates premium drops by state, income, plan.
- CBO-aligned methodology.

**Outputs**
- Policy impact dashboards
- Budget-neutral proofs

### E. National Price Transparency Engine (NPTE)
**Purpose**: Verify posted prices and enforce disclosure compliance.

**Capabilities**
- Computer vision + NLP to verify posted prices in clinics.
- Auto-scrapes insurer/provider price disclosures.
- Flags non-compliance for Medicare/Medicaid providers.

**Outputs**
- Real-time compliance map
- Fines automation

---

## 3. Data Sources
- CMS claims
- Medicare Part D
- Medicaid MCOs
- OECD pricing
- Insurer filings
- Provider fee schedules
- PBM contracts (subpoena-backed)
- Public postings (computer vision)

---

## 4. AI Stack
- Graph neural networks (kickbacks, collusion)
- LLMs with legal constraint decoding (plain English)
- Causal inference models (premium reduction)
- Computer vision (price list detection)

**Model requirements**
- Auditable outputs
- Non-black-box for court admissibility

---

## 5. Governance & Safety
- No clinical decision-making
- Strict bias audits (income, disability, geography)
- Explainability required for enforcement actions
- Federal data residency only

---

## 6. Success Metrics
- Average drug price reduction (%)
- Insurance premium drop (%)
- PBM rebate leakage eliminated ($)
- % providers compliant with price posting
- Consumer comprehension score (plain English)

---

## 7. Rollout Plan
- **90 days**: Pilot in 5 states
- **180 days**: National Medicare/Medicaid coverage
- **1 year**: Full insurer + PBM enforcement

---

## 8. Why This Wins
- Directly enforces policy, not advisory AI
- Measurable taxpayer savings
- Court-admissible outputs
- Consumer-visible impact

---

## Optional Artifacts (On Request)
- Shorter YC-style PRD
- Deck-ready 1-pager
- Technical annex for HHS/CMS
- Budget + procurement framing
