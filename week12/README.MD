
# REPORT — Environmental Impacts of Data Centres & Digital Platforms

> **Instructions**: Work in **pairs**. Use this template to write your 2–3 page Markdown report. Replace all prompts with your content and delete helper text.

First, choose:
- **One data‑centre operator** (e.g., AWS, Azure/Microsoft, Google, Equinix, Digital Realty, OVH) and
- **One digital platform** (e.g., YouTube, Instagram, Netflix, TikTok, X, or a generative‑AI service).

> Keep claims grounded in the companies’ published reports or reputable analyses. **Link and cite every number.**

---

## 1) Executive summary (≈150 words)
*Give one‑sentence findings for (a) the data‑centre operator or (b) the digital platform. State the single most impactful improvement you recommend to each, with one reason why it would help.*

---

## 2) Case A — Data‑centre operator: <Operator name>

### 2.1 What they report (energy, carbon by scope, water)
*Bullet the most recent **quantitative** facts the operator discloses. Include any notes on Scope 1/2/3, renewable/clean‑power strategy, and **water** (e.g., WUE or water‑reduction initiatives). Each item should end with an inline citation link.*

- Example: "Scope 2 (location‑based) trend in region X …" (source)
- Example: "Water reporting / WUE (if published) …" (source)

### 2.2 LB vs MB in practice (2–4 sentences)
*Explain the difference between **location‑based (LB)** and **market‑based (MB)** emissions for electricity, and why LB is the right view for **engineering choices** (region/time). If available, add one sentence referencing your operator’s cloud carbon tooling (e.g., AWS CCFT, Google Carbon Footprint, Azure Carbon Optimisation) and what it shows.*

### 2.3 Risks & trade‑offs (grid & water) (≈1 paragraph)
*Discuss siting/latency vs. carbon trade‑offs and **water** considerations (evaporative vs air/refrigerant cooling; potential **peak‑day water spikes**). Cite at least **two** sources here.*

---

## 3) Case B — Digital platform: <Platform name>

### 3.1 What’s public (policies, metrics)
*Summarise what the platform or its parent company reports about energy/carbon (by scope where applicable) and any relevant targets or initiatives. Use concrete numbers where possible and cite.*

### 3.2 Operational realities & carbon‑aware opportunities (≈1 paragraph)
*Identify the dominant workloads (e.g., video streaming vs. AI inference) and describe **one** realistic way to reduce LB emissions **without harming user experience** (e.g., time‑shifting non‑urgent batch work, region choice for background analytics, demand‑shaping during dirty hours). Cite at least one supporting source.*

### 3.3 Water awareness (3–5 sentences)
*If the platform operates first‑party data centres (or relies heavily on hyperscalers in water‑stressed regions), note potential WUE/peak‑day implications. If no data is available, state that and explain what should be reported.*

---

## 4) Two concrete recommendations (≈150–200 words total)
- **For the operator**: *Write 2–4 sentences. Make it specific, feasible this year (e.g., expand region‑level LB transparency; heat‑reuse; publish WUE and peak‑day capacity; carbon‑aware job slots).*  
- **For the platform**: *Write 2–4 sentences. Example themes: default carbon‑aware scheduling for non‑urgent tasks; nudge background jobs to low‑carbon regions; lightweight formats/bitrates at no QoE loss; publish more granular impact data.*

---

## References (numbered list with links)
*List every source you cited, as a numbered list. Use direct links to official reports or reputable analyses. Example:*  
1. *Organisation/Report title (Year).* [Link](https://example.org)  
2. *Provider tool or dashboard doc.* [Link](https://example.org)

> **Tips**: Prefer recent operator/platform sustainability reports; electricity‑sector analyses (e.g., IEA/EIA); major cloud carbon‑tool docs (AWS CCFT / Google Carbon Footprint / Azure Carbon Optimisation). Match each number to an inline citation in the text like this: `[1]`.

---

## Optional appendix (delete if unused)
- **Figure A1**: *Intensity vs time for two regions with your recommended window highlighted.*
- **Data extraction notes**: *Where you pulled numbers from (page/table), any assumptions.*
- **Glossary (one‑liners)**: *LB, MB, WUE, Scope 1/2/3.*

---

### Formatting hints (delete after drafting)
- Use short paragraphs, bullets, and tables sparingly for clarity.
- Keep units consistent (e.g., gCO₂/kWh; kgCO₂). If you compute anything, show the formula.
- Prefer **location‑based** data for comparisons across regions/times; mention MB only to explain the accounting difference.
- Avoid vague claims (e.g., “green”, “sustainable”) unless backed by a specific metric and citation.
