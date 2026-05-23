# 🚚 BDM Capstone Project: "Optimizing Revenue for a Freight Forwarding Company"
---

![Project](https://img.shields.io/badge/Project-Capstone-blue)
![Type](https://img.shields.io/badge/Type-Independent%20Research-yellow)
![Problem](https://img.shields.io/badge/Problem-Revenue%20Optimization-red)
![Domain](https://img.shields.io/badge/Domain-Business%20Data%20Management-violet)
![Tools](https://img.shields.io/badge/Tools-Excel-217346?logo=microsoft-excel-teal)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)


## 📌 Executive Summary

This capstone project is an in-depth, six-month Business Data Management (BDM) research aimed at breaking a five-year revenue stagnation cycle for a **Multinational Freight Forwarding Company**. Headquartered in Gurugram, India, the enterprise is a subsidiary of a historic Japanese conglomerate with over a century of logistics heritage and operations spanning 29 countries.

Despite a rapidly growing Indian logistics market, the company struggled to scale its domestic B2B revenue over the past five years. By restructuring over 10,000 transaction records, performing multi-dimensional segment analyses, and evaluating digital capabilities, this project identifies critical internal bottlenecks and delivers a data-backed strategic roadmap for targeted market expansion and digital transformation.

---

## 🎯 The Business Challenge & Revenue Mechanics

The enterprise manages two primary logistics revenue streams: **Nominated Shipments** and **Direct Shipments**.

* **Nominated Shipments** are routed through the global corporate network and depend heavily on the company's international reputation and existing overseas contracts rather than local sales efforts[cite: 4].
* **Direct Shipments** are secured locally via regional sales pitches, active client relationships, and marketing pipelines.

Initial analysis revealed that the overall corporate revenue stagnation was heavily influenced by the Nominated Shipments stream. Because Nominated Shipments are largely outside the direct operational control of the Indian subsidiary, the only viable strategic path to break the stagnation was to drastically optimize and scale the **Direct Shipments** stream.

The primary mandates of this research were to:

* Diagnose the underlying root causes limiting growth in local Direct Shipments.
* Clean, aggregate, and normalize multi-sheet, disjointed operational sales workbooks.
* Identify high-value, under-penetrated commodity channels and trade corridors.
* Design an optimized Customer Relationship Management (CRM) framework and modern B2B marketing protocol to reverse client attrition.

---

## 🛠️ Data Engineering & Handling Real-World Constraints

Translating raw, enterprise-level logistics logs into reliable business intelligence required substantial data cleaning. The project involved processing **10,000+ transaction records** consolidated across **9 regional hubs**, requiring extensive schema adjustments to bypass manual data-entry flaws and the absence of a unified ERP system.

* **Massive Data Reclamation:** Audited and reclassified approximately **30%** of the dataset. This included parsing unstructured comment logs to correctly relabel misclassified shipment modes and salvage massive volumes of data initially categorized as "Unknown" commodities.
* **Fragmented Data Consolidation:** Reconciled decentralized accounting workbooks spanning consecutive financial years into a master structural database, filling reporting gaps left by the absence of a regional ERP environment.
* **Feature Engineering for Billing Integrity:** Handled zero-value Chargeable Weight (CW) fields by building a multi-class operational schema (`CC-AI`, `CC-AE`, `CC-OI`, `CC-OE`) to isolate pure "Customs Clearance" entries, recognizing that customs documentation billing relies on overall cargo valuations rather than weight-based freight pricing.
* **Geographic Normalization:** Parsed and cleaned mixed formats of abbreviated international airport and port codes into uniform destination attributes.

---

## 📊 Analytical Methodology

The diagnostic phase combined quantitative database modeling with qualitative service marketing frameworks.

### Quantitative Frameworks

* **Granular Trend Modeling:** Analyzed timeline variations in localized Revenue and Gross Profit across different freight options (Air/Ocean, Import/Export) to capture structural patterns of cyclical disruptions, specifically identifying severe dips in Q3 timelines.
* **Cross-Segment Matrix Analysis:** Constructed conditional matrix layers (*Commodity Verticals vs. Transit Modes* and *Regional Hubs vs. Customer Profiles*) to differentiate profitable anchor segments from systemic financial leaks.
* **Unit Economics & KPI Development:** Quantified operational efficiency across regional territories by establishing ratios for pricing quality and margin sustainability: Revenue per Chargeable Weight (Revenue/CW), Profit/CW, Cost/CW, and relative expense-to-sales ratios.

### Qualitative Frameworks

* **Macro Market Research:** Evaluated national logistics infrastructure overhauls, industry growth trends (projected 18% CAGR by FY30), and digital integration levels across evolving freight marketplaces.
* **Operational Capability Auditing:** Evaluated the company's B2B digital footprint and CRM frameworks to identify service gaps.

---

## 📈 Key Findings & Quantifiable Results

| Analytical Domain | Data-Driven Insights |
| --- | --- |
| **Financial Growth Matrix** | **Direct Sales grew by 7.40% year-over-year.** While overall company revenue faced stagnation due to Nominated Shipments, the Direct Shipment stream maintained profitability and showed top-line growth, proving it is the optimal lever for future scaling. |
| **Unit Logistics Efficiency** | **Revenue/CW surged by ~32%** while **Profit/CW saw a ~51% upward shift.** This confirms that despite market volatility, the firm successfully targeted and managed higher-yield, more valuable contract sizes. |
| **Operational Anchor Points** | **Automotive Components** moving via **Air Import (AI)** served as the core commercial driver. The **Delhi (DEL) branch outperformed the second-largest regional hub by over 2.5x.** This dominance is directly attributed to its proximity to IGI Airport (India's capital hub) and the company's deep-rooted Japanese MNC heritage, which secures heavy volume across Japan Trade Lanes. |
| **Systemic Resource Leaks** | Critical export corridors (Air/Ocean Export) remained severely underutilized. High-volume categories like **Textiles, Apparels, and Raw Materials** consumed significant operational bandwidth while generating unviable bottom-line performance. |
| **Client Pipeline Attrition** | Data revealed a sharp **48% drop in new customer acquisition share** YoY. Analysis linked this to a dangerous over-reliance on legacy accounts, inadequate CRM tracking, and a lack of active B2B digital marketing pipelines. |

---

## 💡 Strategic Recommendations

Based on the quantitative and qualitative findings, the following actionable turnaround playbook was proposed:

* **Deploy Account-Based Marketing (ABM):** Shift resources away from low-yield commodities (Textiles/Apparel) and pivot toward hyper-targeted B2B campaigns focused on high-margin, emerging Indian export sectors like **Semiconductors, Chemicals, and Electronic Goods**.
* **Enterprise Software Infrastructure Mandate:** Transition the enterprise away from detached manual spreadsheets by implementing a centralized ERP system to eliminate data categorization gaps ("Unknown" entries). Pair this with a dedicated Digital CRM to monitor sales funnels and prevent new-client attrition.
* **Territorial Restructuring:** Launch a formal internal review to investigate the extreme operational performance gaps observed in stagnant regional branches (e.g., AMD, LDH, CCU, HYD) and replicate the Delhi hub's Air Import success models.
* **Digital Acquisition Optimization:** Restructure regional web presence with localized Indian landing pages, targeted local SEO, and branch-specific feedback capture channels directly tied to incoming CRM lead generation.

---

## 📂 Repository Structure

* **`BDM Project Proposal Report.pdf`** - Establishes the initial problem boundaries, project timeline dependencies, operational assumptions, and methodology blueprints.
* **`BDM Project MidTerm Report.pdf`** - Details the rigorous data-engineering pipeline, formatting rules, baseline ratio matrices, and early exploratory data patterns.
* **`BDM Project FinalTerm Report.pdf`** - The definitive strategic text containing completed cross-segment diagnostic matrices, external macro market analysis, unit KPI results, and the finalized actionable business advisory plan.
* **`BDM Project Presentation.pdf`** - The executive pitch deck translating corporate findings, operational bottlenecks, and recommended tactical pivots into presentation slides.
* **`Glossary Table for BDM Project.pdf`** - Contains all key terms, definitions, and abbreviations used in the dataset and reports.
