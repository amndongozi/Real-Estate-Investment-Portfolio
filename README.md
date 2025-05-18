# 📊 Real-Estate-Investment-Portfolio

I designed this Power BI dashboard to visualize portfolio performance and forecast trends across commercial and multifamily real estate assets. Commercial assets include office, retail, and industrial properties used for business purposes, while multifamily assets refer to residential buildings with multiple rental units, such as apartments. The dashboard presents actual and predicted Gross Asset Value (GAV) on a quarterly basis, using an XGBoost model trained on time series and panel data. It highlights key drivers influencing asset value and surfaces operational insights using review-based indicators. Built to support strategic planning, the dashboard combines forecasting accuracy with intuitive visual storytelling for investment decision-making.

---

## 🔍 Key Insights from the Dashboard

### 📌 Review Score Distribution *(Top-Left)*
- Compares review ratings between **operating** and **disposed** properties  
- Operating assets show **higher satisfaction levels**, signaling stronger tenant experience and operational health

### 📌 Top Predictors of Asset Value *(Top-Right)*
- **Recent GAV (last quarter)** is the most important predictor for next-quarter value  
- This shows **strong temporal momentum** in valuations, as asset values typically evolve gradually  
- Real estate investments don’t fluctuate dramatically, supporting stable short-term forecasting

### 📌 GAV Trends by Property Type *(Bottom-Left)*
- Line chart tracking GAV over time for **commercial** and **multifamily** portfolios  
- Highlights **steady multifamily growth** and a **commercial rebound post-2022**

### 📌 Forecast Accuracy *(Bottom-Right)*
- Compares **actual vs. predicted** GAV  
- The close alignment demonstrates the **model’s reliability** for quarterly forecasting



![image](https://github.com/user-attachments/assets/5715fe17-3b39-42ae-b159-e97da294b59e)

📌 *Dashboard built in Power BI using proprietary data (not shared). Visuals provided for demonstration purposes only.*
