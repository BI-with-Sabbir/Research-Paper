# 🫠 Visual Dashboards for Multi-Domain Assessment of Organ Procurement Organization Performance

## 📄 Overview
This repository presents the research paper **"Visual Dashboards for Multi-Domain Assessment of Organ Procurement Organization Performance,"** which introduces a public-facing, interactive dashboard built to assess and compare the performance of Organ Procurement Organizations (OPOs) in the United States across multiple domains. Using data from 2010–2020, the project highlights disparities in organ procurement outcomes, focusing on equitable access and performance benchmarking.

## 🧠 Abstract
With stakeholder focus on the United States organ procurement system, there is a need for tools that permit comparative assessment of organ procurement providers. We developed a public-facing dashboard for OPOs using multi-source data from 2010–2020, enabling visualization of OPO performance metrics including:
- CMS-defined donors per 100 donation-consistent deaths
- Donation after circulatory death (DCD) procurement
- Older and minority donor populations
- Procurement in small hospitals
- Procurement of patients without significant drug history

Patterns of high-performing OPOs were identified, and 74% of differences in procurement rates were explainable via model variables. Variance in performance was more reproducibly driven by differences among minority patient groups and small hospital recovery efforts than geographic DSA conditions. This tool supports transparency, benchmarking, and quality improvement for stakeholders and policy-makers.

## 🧾 Keywords
`OPO` • `Organ Procurement` • `Dashboard` • `CMS` • `HRSA` • `Transplantation Policy` • `Data Visualization` • `Shiny` • `Healthcare Analytics`

---

## 📁 Repository Structure
```
organ-procurement-dashboard/
├— paper.pdf                    # Full research paper
├— README.md                    # Project overview
├— dashboard_samples/           # Screenshots or demo of the dashboard
├— data/                        # Public/synthetic datasets (if shareable)
├— notebooks/                   # R code or Jupyter notebooks (if any)
├— references/                  # Citations or related work
└— app/                         # Shiny app files (ui.R, server.R)
```

---

## 🌐 Live Dashboard (Demo)
A pilot online dashboard was developed using R's **Shiny** framework and deployed via **Heroku**. It visualizes key OPO performance domains, benchmarked against national averages.

> **Demo:** _[[Insert Public URL if available](https://opo-dashboard.herokuapp.com/)]_  
> *(If the live dashboard is unavailable, screenshots are provided in the `dashboard_samples/` folder.)*

---

## 📊 Key Performance Metrics Visualized
- 🕛 CMS metric: Donors per 100 CALC deaths
- 🧓 Older Donors (65–75 years)
- 🔄 DCD Donors (<65 years)
- 🏥 Small Hospital Procurement
- 🧬 Minority Group Performance (e.g., Black & non-White donors)
- ❌ Procurement without drug-related death history

These were positioned on a radial dashboard to enable quick performance benchmarking across OPOs.

---

## 🧪 Methods
- Multi-source data (SRTR, OPTN, CDC, HIFLD)
- DSA-level analysis of hospital characteristics and patient demographics
- Shiny-based dashboard creation for visualization
- Statistical modeling using R: generalized linear models, ICC, marginal R², quartile-based comparisons

---

## 📈 Results Summary
- 2.94× higher DCD procurement in top-performing OPOs (Quartile 1 vs. 4)
- 61% of variation in procurement performance was attributed to differences between OPOs (ICC = 0.61)
- Minority population engagement and small hospital recovery were critical differentiators
- Dashboard showed clear concentric quartile performance patterns across domains

---

## 📌 Citation
```
"Visual Dashboards for Multi-Domain Assessment of Organ Procurement Organization Performance." American Journal of Transplantation, 2023. GitHub, 2025.
```

---

## 📬 Contact
For questions or collaborations:  
 
🔗 [[LinkedIn Profile or Website](https://www.linkedin.com/in/shabbir-hossain-rossi/)]

---

## 📃 License
This research project is made available for academic and educational purposes. Please contact the author for permissions regarding data use and redistribution.


