# 🌫️ Forecasting PM2.5 and PM10 Pollution in East Jakarta using SARIMA  
📄 Published on ResearchGate | DOI: [10.13140/RG.2.2.10480.16646](https://doi.org/10.13140/RG.2.2.10480.16646)

This project presents a time series forecasting analysis using **Seasonal ARIMA (SARIMA)** models to predict PM2.5 and PM10 air pollution levels in **East Jakarta (DKI 4)**. The findings aim to support **early warning systems** and **air quality policy planning**.

---

## 🎯 Objective

To identify the most polluted sub-region in DKI Jakarta and build accurate SARIMA models to forecast air pollutant concentrations (PM2.5 & PM10) for **September–November 2024**.

---

## 📦 Dataset

- **Source**: Satu Data Indonesia  
- **Timeframe**: Jan 2020 – Aug 2024  
- **Data**: Daily pollution measurements from 5 air quality monitoring stations in DKI Jakarta  
- **Features**: PM2.5, PM10 (resampled to monthly average)

---

## ⚙️ Methodology

- **Framework**: CRISP-DM  
- **Techniques**:
  - Time Series Preprocessing & Resampling  
  - ADF Stationarity Test  
  - SARIMA parameter tuning via ACF/PACF  
  - K-Fold Cross Validation  
  - Statistical Validation: Ljung-Box & Shapiro-Wilk  
- **Tools**: Python (Colab), R Studio

---

## 📈 Models & Accuracy

| Pollutant | Best Model              | Accuracy | RMSE  | MAPE   |
|-----------|-------------------------|----------|-------|--------|
| PM2.5     | SARIMA (1,0,0)(1,1,0)[12] | **91.15%** | 10.32 | 8.85%  |
| PM10      | SARIMA (3,0,2)(1,0,0)[12] | **91.13%** | 6.21  | 8.87%  |

✅ Both models passed cross-validation and statistical assumptions.

---

## 💡 Key Insights

- **East Jakarta (DKI 4)** is the most polluted sub-region.  
- PM2.5 levels are forecasted between **86–105 μg/m³**, exceeding WHO’s safe limit by up to **21×**.  
- PM10 remains within safe limits (54–64 μg/m³).  
- Results support urgent **policy recommendations** for high-risk months.

---

## 📌 Publication Details

- 🔗 **DOI**: [10.13140/RG.2.2.10480.16646](https://doi.org/10.13140/RG.2.2.10480.16646)  
- 📚 Published on **ResearchGate**, 2024  
- 🏫 Presented under Universitas Indonesia – FMIPA

---
## 📄 License

This research is published and licensed for academic use only. Please cite the publication if used in derivative work.
