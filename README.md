# Kidney Transplant Immunosuppression Dashboard

A **flexdashboard** that compares the safety and efficacy of abatacept conversion versus standard belatacept maintenance in adult kidney transplant recipients.  
**Live demo:** https://github.com/Wen200802/finaldashboard/  

---

## 📊 Live Dashboard

Open the interactive dashboard here:  
https://github.com/Wen200802/finaldashboard/  

---

## 🔧 Installation

1. **Clone this repository**  
   git clone https://github.com/Wen200802/finaldashboard.git  
   cd finaldashboard  

2. **Install required R packages**  
   Rscript -e 'install.packages(c("flexdashboard", "plotly", "DT", "ggplot2", "htmlwidgets", "dplyr"))'  

3. **Render locally** (optional)  
   Rscript -e 'rmarkdown::run("Final project 4a.Rmd")'
  

---

## 🗂️ Data

 **Confidential clinical trial data** from a prospective, intention‑to‑treat, randomized controlled study comparing abatacept conversion vs. belatacept maintenance in kidney transplant patients.  
 - **Sample size:** 86 first‑time adult renal transplant recipients (≥18 years, any gender/race/ethnicity)  
 - **Collection:** Scheduled blood draws for PK/PD, safety labs, HLA testing, and efficacy assessments at baseline, Month 3, 6, 9, 12, and 24  
 - **Period:** Enrollment over 1.5 years; 24 months follow‑up; total study span ~3.5 years  

*(Raw data are confidential and not included.)*

---

## ⚙️ Usage

- Navigate to the **“Dataset Description”** tab to review study design and data collection protocol.  
- Hover over any point in the main plot to see patient‑level metrics (arm, timepoint, eGFR, etc.).  
- Use the legend toggles to filter by treatment arm.  

---

## 🔗 Source Code

This repository contains the RMarkdown (Final project 4a.Rmd) and all supporting scripts to generate the dashboard widgets.  

---

## 🌟 Project Impact

This trial addresses a critical need to optimize immunosuppression in kidney transplant patients by comparing abatacept conversion with standard belatacept maintenance. Its findings will inform evidence‑based guidelines to personalize therapy, improve long‑term graft survival, and minimize treatment‑related toxicity.  

