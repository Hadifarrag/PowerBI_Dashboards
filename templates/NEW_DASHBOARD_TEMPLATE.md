# 📋 Template for Adding New Dashboards

Whenever a new Power BI or BI dashboard is ready to be added to this repository, follow this standardized template:

## 1. Directory Structure
Create a new folder using the convention: `XX_Dashboard_Name/` (where `XX` is the next sequential number):
```text
XX_Dashboard_Name/
├── README.md                     # Markdown summary using the template below
├── preview.png                   # High-res capture (rendered from PDF/PBIX, min 1920x1080)
├── Dashboard_Name.pdf            # Exported report PDF (vector quality)
├── Dashboard_Name.pbix           # (Optional) Power BI file if under 100MB
└── data/                         # (Optional) Sample CSV/Excel or data dictionary
    └── dataset.csv
```

## 2. README.md Template
```markdown
# [Icon] [Dashboard Name]

![Dashboard Preview](preview.png)

## 📌 Executive Summary
Brief 2-3 sentence overview of the business domain, target audience, and primary decision problem solved.

---

## 🎯 Key Performance Indicators (KPIs)
- **Primary Metric 1:** `Value`
- **Primary Metric 2:** `Value`
- **Primary Metric 3:** `Value`

---

## 🔍 Detailed Analysis & Visuals
### 1. [Key Visual Title]
Analysis and findings.

### 2. [Key Visual Title]
Analysis and findings.

---

## 📁 Files in This Directory
- `Dashboard_Name.pdf`
- `preview.png`
- `data/`
```

## 3. Checklist for Updating Portfolio
- [ ] Add entry to root `PowerBI_Dashboards/README.md` catalog table.
- [ ] Copy preview PNG and PDF to `Portfolio/assets/dashboards/`.
- [ ] Add the dashboard article card in `Portfolio/dashboards.html`.
- [ ] Commit and push to both repositories (`PowerBI_Dashboards` and `Hadifarrag.github.io`).
