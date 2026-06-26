# San Francisco Overdose EDA: Uncovering Seasonal Patterns in the Opioid Crisis

**Externship:** TruBridge x Extern  
**Author:** Ryan Park

---

## Overview

This project analyzes seasonal patterns in unintentional drug overdose deaths in San Francisco using data from the SF Office of the Chief Medical Examiner (2020–2025). The goal is to identify when overdose deaths peak throughout the year, empowering public health officials, harm reduction managers, and policy planners to deploy timely, proactive interventions.

---

## Research Questions

- What are the monthly patterns in unintentional overdose deaths in San Francisco (2020–2025, aggregated by month)?
- Which months tend to have the highest and lowest totals?
- Is the average monthly total meaningfully different from a practical baseline?
- What is the probability that a given month exceeds a high-risk threshold?

---

## Key Findings

- Overdose deaths follow a clear **seasonal rhythm**, rising sharply each **spring and early summer (March–June)**
- Monthly deaths average **323**, peaking at **426 in March** and dropping to **244 in November**
- Nearly **1 in 4 months exceeds 350 deaths**, meaning high-risk periods are not rare — they are recurring
- The ~200-death gap between peak and trough months underscores the urgency of seasonal resource planning

---

## Recommended Action Cycle

| Period | Action |
|--------|--------|
| Feb–Mar | Expand naloxone access and build outreach capacity before the surge |
| Mar–Jun | Deploy mobile health units and overdose prevention teams |
| Jul–Aug | Monitor and adjust strategies using real-time data |
| Sep–Nov | Evaluate outcomes and plan for the next cycle |

---

## Files

| File | Description |
|------|-------------|
| `Overdose_EDA_Report.ipynb` | Full EDA notebook with analysis and visualizations |
| `Overdose_EDA_Story_Notebook.ipynb` | Narrative storytelling notebook for non-technical audiences |
| `overdose_eda_story.py` | Python script version of the EDA |
| `overdose_deaths_by_month_normalized.csv` | Cleaned dataset: monthly aggregated overdose deaths (2020–2025) |
| `San-Franciscos-Hidden-Overdose-Season.pdf` | Final presentation report |

---

## Tools & Libraries

- **Language:** Python
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`
- **Data Source:** SF Office of the Chief Medical Examiner — Preliminary Unintentional Drug Overdose Deaths, 2020–2025
