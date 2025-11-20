# 📊 Data Science Assignment – Web3 Trading Team  
### Candidate: Pratiksha Mohite

This repository contains the full submission for the Data Science assignment focused on analyzing the relationship between **crypto market sentiment (Fear–Greed Index)** and **trader behavior** using **Hyperliquid historical trade data**.

---

## 📁 Folder Structure (Required Format)
ds_pratiksha_mohite/
├── notebook_1.ipynb # Main Google Colab notebook link (added below)
├── csv_files/ # Processed CSV outputs (generated during analysis)
├── outputs/ # All charts/visuals exported from notebooks
├── ds_report.pdf # Final insights report
└── README.md # Documentation (this file)

---

## 🔗 Google Colab Notebook Link  
https://colab.research.google.com/drive/1cigvgbhFbBqdBh2aLmdJ1ytIp_Wm4A2o?usp=sharing)

---

## 📂 Datasets Used

### 1. **Bitcoin Fear & Greed Index**
- Columns: `timestamp`, `value`, `classification`, `date`

### 2. **Hyperliquid Historical Trader Data**
- Columns: `Account`, `Coin`, `Execution Price`, `Size Tokens`, `Side`,  
  `Timestamp IST`, `Start Position`, `Direction`, `Closed PnL`, `Fee`, etc.

Both datasets were processed and aligned using timestamps to analyze how sentiment affects trading activity and profitability.

---

## 🧠 Objective

- Examine how **trading behavior** (trade count, PnL, volume, risk-taking)  
  aligns or diverges from **crypto market sentiment** (Fear, Neutral, Greed).

- Identify trends that could create smarter automated trading strategies.

---

## 📈 Key Analysis Performed

- Sentiment-wise daily aggregation (Fear vs Greed vs Neutral)  
- Statistical testing (T-test on PnL differences)  
- Correlation analysis between sentiment score & trading metrics  
- Top-performing symbols analysis  
- Profitability and win-rate insights

---

## 📑 Report

The detailed analysis, insights, and interpretations are provided in:

➡️ **ds_report.pdf**

---

## 🚀 Instructions for Evaluators

All work follows the structure required in the assignment brief.  
Notebooks contain clean, reproducible code and outputs.  
All CSV and chart outputs are stored in the corresponding folders.

---

## ✔️ Notes

- This project is structured for immediate upload to GitHub.  
- All notebooks are intended to run on **Google Colab**.  
- No additional setup is required.

---

Thank you for reviewing my assignment!  
— *Pratiksha Mohite*
