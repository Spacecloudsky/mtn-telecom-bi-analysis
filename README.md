[telecom_README.md](https://github.com/user-attachments/files/28924845/telecom_README.md)
# MTN Nigeria Telecom Operations Intelligence

A two-layer analysis of a 10,000-customer MTN Nigeria telecom dataset, built to help telecom leadership understand customer behaviour, network performance, revenue collection risk, and customer experience — at both the operational and executive level.

## Project Structure

This project uses one cleaned dataset, explored at two levels:

**Layer 1 — Python EDA (`MTN_Telecom_EDA_Cleaned.ipynb`)**
Data cleaning and exploratory analysis in pandas and Plotly, answering 10 granular business questions: customer segmentation, churn risk, top users and revenue contributors, KYC compliance, plan performance, network quality by state, payment behaviour, support demand, loyalty/referrals, and device usage patterns.

**Layer 2 — Power BI Dashboard (`Mtn_telecom_powerbi_report.pbix`)**
A 5-page executive dashboard built on the same cleaned dataset, focused on operational and strategic questions: revenue trends, payment status across the customer base, network quality and call-drop rates by state, customer satisfaction, support ticket volume, and a deep-dive into the lowest-performing state.

The two layers answer different questions at different altitudes — Layer 1 is exploratory and customer-level, Layer 2 is aggregated and decision-ready for leadership.

## Dataset

`telecom_customers.csv` — 10,000 simulated MTN Nigeria customer records, including demographics, subscription details, usage metrics (voice, data, SMS), network experience (call drops, quality scores, satisfaction), and payment/behavioural indicators.

## Key Insights

- Network quality and call-drop rates vary significantly by state, with several states (Niger, Borno, Kebbi, Edo, Cross River) consistently underperforming.
- A third of the customer base sits in "Overdue" or "Unpaid" status, representing a significant revenue collection risk.
- No customers in this dataset show zero usage combined with unpaid bills — suggesting low immediate churn risk despite high payment delinquency.
- Support ticket volume is concentrated in specific states, pointing to where customer experience investment would have the most impact.

## Tools

Python (pandas, Plotly Express) · Power BI · CSV

## Files

| File | Description |
|---|---|
| `MTN_Telecom_EDA_Cleaned.ipynb` | Data cleaning + 10-question Python/Plotly EDA |
| `Mtn_telecom_powerbi_report.pbix` | 5-page Power BI executive dashboard |
| `telecom_customers.csv` | Source dataset |
