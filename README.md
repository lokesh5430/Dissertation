# Stock Sentiment and Risk Prediction Dashboard

This repository contains the full pipeline, dataset, and business intelligence (BI) dashboard developed for my MSc dissertation at the University of Greenwich.

The project investigates whether **market sentiment**, when combined with traditional **financial KPIs**, can improve short-term risk prediction across multiple companies. It integrates Python-based sentiment analysis, predictive modelling, and a Power BI dashboard for interactive decision support.

____

## 📂 Repository Structure
---

## 🚀 How to Use
1. Open `stock price and sentiment.ipynb` to see the full workflow:
   - Data collection from Yahoo Finance
   - Sentiment scoring using FinBERT
   - Preprocessing & feature engineering
   - Logistic regression risk prediction
   - Export to CSV for dashboard

2. Load `dashboard_dataset1.csv` into Power BI.

3. Open `risk analysis.pbix` to explore the ready-made dashboard:
   - Stock price vs sentiment trend (line chart)
   - KPI cards (price, average sentiment, risk probability)
   - Risk probability gauge
   - Sentiment heatmap across companies
   - Slicers for company and date range

---

## 📊 Dashboard Features
- **Interactive filtering** by company and time period  
- **Visual comparison** of financial KPIs vs sentiment  
- **Risk probability indicator** (low, medium, high)  
- **Cross-company sentiment heatmap** for quick benchmarking  

---

## ⚖️ Ethical Note
- All financial and sentiment data were collected from **publicly available sources** (Yahoo Finance).  
- No private or personal data were used.  
- Analysis was performed for academic purposes only.  

---

## 📖 Citation
If you use this work, please cite:  
**Bodolla, L. (2025). MSc Dissertation: Stock Sentiment and Risk Prediction Dashboard. University of Greenwich.**

---
