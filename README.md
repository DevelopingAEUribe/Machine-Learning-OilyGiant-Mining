#  Oil Well Profit Forecasting (OilyGiant)

A machine learning project to forecast oil reserve volumes, evaluate financial risk, and select the most profitable region for well development under strict business constraints.

---

##  Project Overview

This project was conducted on behalf of OilyGiant, a synthetic oil company tasked with choosing the most profitable location for developing 200 new oil wells across three possible regions. Using historical geological data and oil reserve volumes, I trained a predictive model and performed a full profitability and risk analysis to recommend the optimal region for investment.

The project combined regression modeling with statistical simulation to deliver business-ready insights.

---

##  Key Objectives

- Predict the volume of oil reserves in new wells using linear regression.
- Evaluate development profitability under a fixed budget constraint.
- Quantify the financial risk of each region using bootstrapping.
- Recommend the best region based on return on investment and risk threshold.

---

##  Tools & Technologies

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Statistical Techniques**: Bootstrapping, Confidence Intervals, RMSE
- **Environment**: Jupyter Notebook

---

##  Workflow Summary

1. **Data Preprocessing**:  
   - Cleaned and explored data from three regional oil datasets.
   - Split data into training and validation sets using a 75:25 ratio.

2. **Model Training**:  
   - Built and validated a linear regression model for each region.
   - Measured model performance using RMSE and average predicted reserves.

3. **Profitability Analysis**:  
   - Created a function to simulate development of 200 wells per region.
   - Calculated ROI based on predicted reserves, development budget, and revenue per barrel.

4. **Risk Assessment**:  
   - Applied bootstrapping (1,000 simulations) to estimate confidence intervals.
   - Calculated probability of financial loss and filtered regions exceeding a 2.5% risk threshold.

5. **Final Recommendation**:  
   - Selected the region with the highest average profit and acceptable risk level.

---

##  Key Results

- Linear regression models predicted reserve volumes with consistent accuracy across all three regions.
- One region showed significantly higher profit with <2.5% risk of loss, making it the ideal investment.
- Bootstrapped profit distributions provided 95% confidence intervals for financial planning.

---

##  Business Impact

This project delivered a clear recommendation for capital allocation based on:
- Data-driven ROI forecasts
- Risk-aware modeling
- Scalable simulation techniques for large financial decisions

---

##  Project Structure
├── oilygiant_profit_forecasting.ipynb
├── data/
│ ├── geo_data_0.csv
│ ├── geo_data_1.csv
│ └── geo_data_2.csv
├── images/
│ └── profit_distributions.png
└── README.md

