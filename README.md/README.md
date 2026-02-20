## RAPIDO ORDERS & REVENUE OPTIMIZATION ANALYSIS
## Project Overview

This project analyzes revenue leakage, pricing fairness, ride cancellations, and captain earnings stability using a Current vs Optimized scenario simulation model built in Power BI.

It demonstrates how pricing and operational adjustments impact:

-Revenue Growth\
-Customer Trust\
-Captain Stability\
-Ecosystem Sustainability

## Dataset Used
<a href="https://drive.google.com/file/d/1J8_VKFCLEpQNFvh2OfDIENu-hLBjqWoH/view?usp=sharing">Click here to view dataset</a>


## Business Questions & KPIs
# Core Business Questions

-Where is revenue leakage happening?\
-How does price per KM impact customer churn?\
-Which distance segments cause drop-offs?\
-How does weather influence pricing fairness?\
-Are captain earnings stable across vehicle types?\
-What happens if pricing is optimized?\

# Key KPIs Tracked

-Booking Conversion Rate\
-Net Revenue Improvement\
-Revenue Leakage\
-Price Per KM\
-Customer Trust Index\
-Captain Stability Indicator\
-Average Customer Rating\
-Earnings per Vehicle Type\
-Cancellation Rate\

# Project Process
# Step 1: Data Collection 

-Extracted ride-level data using SQL (MySQL)

# Step 2: Data Cleaning

-Handled null values\
-Standardized price & distance\
-Feature engineering (KM bins, time slots)

# Step 3: Scenario Engineering

-Built Current vs Optimized logic using DAX\
-Used SELECTEDVALUE() for scenario toggle\
-Applied pricing caps & efficiency rules

# Step 4: KPI Development

-Revenue Loss Measures\
-Trust Index Formula\
-Stability Indicator Calculation

#  Step 5: Dashboard Design

-Multi-page narrative flow\
-Revenue Leakage\
-Pricing Fairness\
-Captain Earnings\
-Sustainability View

# Dashboard Snapshots
<img width="1385" height="776" alt="BUSINESS  OVERVIEW" src="https://github.com/user-attachments/assets/09fb03a2-4874-4744-a76d-c703fbd3bb65" />

<img width="1384" height="774" alt="REVENUE LEAKAGE   CANCELLATIONS" src="https://github.com/user-attachments/assets/b22f918b-694e-49e8-aca0-d4539042fa2d" />

<img width="1381" height="774" alt="CAPTAIN PRODUCTIVITY   EARNINGS" src="https://github.com/user-attachments/assets/c88a5dc7-eb68-44d3-b6d9-a860f9d020e7" />

<img width="1382" height="776" alt="CUSTOMER PRICE FAIRNESS   CHURN RISK" src="https://github.com/user-attachments/assets/f6f68e88-dfbc-4c9e-91e7-2ea4dbcfff48" />

<img width="1379" height="775" alt="🕒   BUSINESS SUSTAINABILITY  ECOSYSTEM HEALTH" src="https://github.com/user-attachments/assets/5b63cf2c-48d2-416b-987a-3aeed57ec197" />

 # View Interactive Dashboard
 <a href="https://app.powerbi.com/view?r=eyJrIjoiZDJmZTkyZmItZGQyMC00NjY5LWJkZjMtOTRlMzU5Y2I0MGQ1IiwidCI6IjA4MGE5YjRhLTdiNDAtNDJmMC1hMmMwLTU4YzFhNzZmNGNiOCJ9">Click here to view Power BI Dashboard</a>


 # Key Project Insights

-Long-distance rides contributed highest revenue leakage\
-Rainy weather pricing increased churn risk\
-Price imbalance across vehicles impacted trust perception\
-Optimized pricing improved revenue by +227.84K\
-Captain earnings increased across Cab, Auto & Bike\
-Scenario simulation showed ecosystem-wide stability improvement

# Tools & Technologies Used

-Power BI (DAX, Data Modeling, Scenario Logic)\
-SQL (MySQL)\
-Python (Pandas, NumPy, Matplotlib)\
-Excel\
-Jupyter Notebook

# Final Conclusion

-This project demonstrates how data-driven pricing optimization can:\
-Reduce revenue leakage\
-Improve customer trust\
-Stabilize captain earnings\
-Strengthen long-term business sustainability\
The dynamic Current vs Optimized simulation engine enables leadership to quantify impact before implementing pricing changes.


# Repository Structure:
RAPIDO-ORDERS-OPTIMIZATION/
│
├── data/  \
│   └── rapido_orders_dataset.csv \
│
├── images/  \
│   ├── price_fairness.png \
│   └── sustainability_dashboard.png \
│
├── notebooks/  \
│   └── data_cleaning.ipynb \
│
├── dashboard/  \
│   └── rapido_dashboard.pbix \
│
└── README.md
