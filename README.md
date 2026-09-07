## 📊 Project Overview

A comprehensive end-to-end financial analytics project covering revenue forecasting, churn prediction, and profitability analysis.

### 🎯 Business Objectives

1. **Revenue Forecasting** - Predict future revenue with 90%+ accuracy using time series models.
2. **Churn Prediction** - Identify at-risk customers before they leave.
3. **Profitability Analysis** - Segment customers and optimize resource allocation.
4. **Cohort Analysis** - Track customer behavior and retention over time.

### 💡 Key Results

- 📈 **Revenue Forecast**: ${forecast.sum():,.0f} predicted for next 12 months
- 🎯 **Churn Model Accuracy**: {churn_results[best_churn_model_name]['roc_auc']:.1%}
- 💰 **Identified Value**: ${at_risk_mrr * 12:,.0f} annual revenue at risk
- 👥 **Customer Segments**: {optimal_k} distinct groups with targeted strategies

---

## 📁 Project Structure

```text
financial-operations-analytics/
├── financial_customers.csv         # Customer master data
├── financial_transactions.csv      # Transaction history
├── monthly_revenue.csv             # Aggregated monthly metrics
│
├── financial_analytics.py          # Complete analysis script
├── EXECUTIVE_SUMMARY_FINANCIAL.txt # Executive report
├── kpi_summary.txt                 # Key metrics summary
│
├── at_risk_customers.csv           # High churn risk list
├── rfm_segmentation.csv            # RFM customer segments
│
├── financial_viz/                  # All visualizations (16 files)
│   ├── 01_initial_exploration.png
│   ├── 02_ts_decomposition.png
│   ├── 03_acf_pacf_analysis.png
│   ├── 04_arima_forecast.png
│   ├── 05_prophet_forecast.png
│   ├── 06_prophet_components.png
│   ├── 07_churn_analysis.png
│   ├── 08_churn_model_evaluation.png
│   ├── 09_churn_feature_importance.png
│   ├── 10_risk_stratification.png
│   ├── 11_cohort_retention.png
│   ├── 12_revenue_cohorts.png
│   ├── 13_rfm_analysis.png
│   ├── 14_clv_analysis.png
│   ├── 15_profitability_dashboard.png
│   └── 16_FINAL_EXECUTIVE_DASHBOARD.png
│
├── README.md                       # This file
└── requirements.txt                # Python dependencies
```
