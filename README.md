# Sinarmas Land — Data Analysis

Capstone 2 — Data Analysis Portfolio Project

## Project Overview

Analisis data billing dan property management untuk mengidentifikasi risiko tunggakan, peluang revenue recovery, serta masalah kualitas data pada proses billing.

## Business Questions

1. Township atau cluster mana yang memiliki arrears rate tertinggi?
2. Apakah unit vacant memiliki tingkat tunggakan yang lebih tinggi?
3. Berapa nilai outstanding dan bagaimana distribusinya?
4. Apakah terdapat tunggakan kronis lebih dari 6 bulan berturut-turut?
5. Seberapa besar masalah missing payment method dan contact number?
6. Apakah terdapat anomali pada payment date dan water usage?

## Key Findings

| Metric | Result |
|---|---:|
| Total Invoices | 300,000 |
| Total Outstanding | Rp117.26 Miliar |
| Vacant Units | 6,178 |
| Vacant Arrears Rate | 60.10% |
| Non-Vacant Arrears Rate | 20.18% |
| Missing Payment Method | 90,278 |
| Missing Contact Number | 5,000 |
| Paid Before Handover | 6,291 |
| Water Usage Issues | 3,000 |
| Chronic Arrears Streaks (>6 months) | 1 |
| Chronic Arrears Outstanding | Rp4.45 juta |

## Dashboard

**Interactive Dashboard:** [Open Looker Studio Dashboard](PASTE_LOOKER_STUDIO_LINK_HERE)

Dashboard mencakup:
- Executive Overview
- Collection & Arrears
- Data Quality & System Control

## Data Analysis Notebook

Notebook berisi proses:
- Data Understanding
- Data Cleaning
- Data Validation
- Exploratory Data Analysis (EDA)
- Diagnostic Analysis
- Statistical Analysis
- Business Insights
- Conclusion & Recommendation

**Notebook:** [Open Analysis Notebook](./notebook/Sinarmas_Land_Data_Analysis.ipynb)

## Presentation

**Capstone 2 Presentation:** [Open Presentation](./presentation/Sinarmas_Land_Capstone_2.pdf)

## Project Presentation Video

**YouTube:** [Watch Project Presentation](PASTE_YOUTUBE_LINK_HERE)

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- Looker Studio
- Jupyter Notebook

## Project Structure

```
data-analysis/
├── README.md
├── presentation/
│   └── Sinarmas_Land_Capstone_2.pdf
├── notebook/
│   └── Sinarmas_Land_Data_Analysis.ipynb
├── dashboard/
│   └── dashboard_preview.png
└── assets/
    └── screenshots/
```

## Data Privacy Notice

The original dataset may contain property, owner, contact, unit, invoice, or billing-related information. For a public portfolio repository, do not publish raw sensitive records unless you have the appropriate authorization. Use anonymized or approved portfolio data instead.
