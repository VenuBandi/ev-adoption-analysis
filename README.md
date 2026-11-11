# U.S. Electric Vehicle Adoption Analysis

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://python.org)
[![Stars](https://img.shields.io/github/stars/VenuBandi/ev-adoption-analysis?style=social)](https://github.com/VenuBandi/ev-adoption-analysis)

Data analysis of U.S. electric vehicle adoption — state-level registrations and public charging infrastructure growth from 2007 to 2024.

---

## Key Questions

- Which states lead in EV adoption, and how concentrated is it?
- How has public charging infrastructure grown over time?
- Does charging supply keep pace with EV adoption?

## Data Sources

| File | Source |
|---|---|
| `ev_registrations_by_state_2023.xlsx` | U.S. DOE — EV Registrations by State (2023) |
| `ev_charging_infrastructure.xlsx` | U.S. DOE — Public EV Charging Ports & Stations (2007–2024) |

## Key Findings

- EV adoption is heavily concentrated — top 3 states hold a large share of all registrations
- Public charging ports have grown from **417 (2007)** to over **170,000 (2024)**
- Growth in charging infrastructure is exponential, mirroring EV adoption trends

## Repo Structure

```
ev-adoption-analysis/
├── notebooks/
│   └── ev_analysis.ipynb
├── data/
│   ├── ev_registrations_by_state_2023.xlsx
│   └── ev_charging_infrastructure.xlsx
└── docs/
    ├── The_Electric_Inevitability_with_key_questions.pptx
    └── Operational_EV_Project_Plan.docx
```

## Setup

```bash
git clone https://github.com/VenuBandi/ev-adoption-analysis
cd ev-adoption-analysis
pip install -r requirements.txt
jupyter lab notebooks/ev_analysis.ipynb
```

## Stack

`Python` · `Pandas` · `Matplotlib` · `Seaborn` · `openpyxl`
