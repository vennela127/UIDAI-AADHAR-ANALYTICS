**UIDAI Aadhaar Analytics**

Unlocking Societal Trends, Anomalies, and Predictive Indicators in Aadhaar Enrolment and Updates

**Overview**


This project analyses India’s Aadhaar ecosystem using official UIDAI enrolment, demographic update, and biometric datasets. It transforms large-scale raw data into actionable insights for fraud detection, capacity planning, and system optimisation.

The analysis shows a clear shift from Aadhaar growth to a maintenance-driven system, dominated by updates, biometric corrections, and regional imbalances.

**Objectives**


Identify long-term trends and activity patterns

Detect anomalies beyond normal seasonality

Analyse age-group and regional drivers of system load

Forecast future Aadhaar demand with uncertainty awareness

Translate insights into practical, policy-oriented solutions

**Datasets Used**


Aadhaar Enrolment: Age-wise and state-wise new registrations

Demographic Updates: Address and identity corrections reflecting migration and lifecycle changes

Biometric Updates: Fingerprint/iris updates and age-related volatility

(All datasets processed from UIDAI-provided ZIP CSV files.)

**Methodology**


Preprocessing: Cleaning, monthly aggregation, and 30-day normalization

Trend Analysis: STL decomposition (trend, seasonality, residuals)

Anomaly Detection: Isolation Forest on STL residuals with cross-dataset overlap analysis

Forecasting: 12-month Prophet forecasts with confidence intervals

**Key Insights**


Aadhaar has transitioned from enrolment growth to maintenance dominance

Adults drive most enrolments and updates; children show higher biometric volatility

Activity is concentrated in a few states, with uneven national coverage

Strong seasonal patterns and calendar bias affect raw trends

Clustered anomalies across datasets indicate system-level stress

Forecasts highlight upcoming peak-demand periods

**Proposed Solutions**


Fraud Prevention: Class 10 certificate linkage (age 16+) with centralised verification

Aadhaar at Birth: Hospital-based enrolment using birth certificates

Smart Load Management: Location-based centre discovery, slot booking, priority access

Preventive Biometrics: Scheduled biometric updates every 1–3 years

**Impact**


Reduces fraud and duplicate identities

Improves regional capacity planning

Minimises biometric failures and update overload

Enables proactive, data-driven decision-making

**Tech Stack**


Python · Pandas · NumPy · Matplotlib · Statsmodels · Scikit-learn · Prophet
Google Colab
