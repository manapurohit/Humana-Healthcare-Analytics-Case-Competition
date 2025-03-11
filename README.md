# Humana-Mays 2024 Healthcare Analytics Case Competition

## Overview  
This repository contains our work for the **Humana-Mays 2024 Healthcare Analytics Case Competition**. The objective of this competition was to predict **Primary Care Physician (PCP) engagement** for **1.5 million** Medicare Advantage members and provide insights to improve preventive care engagement.

## Problem Statement  
Humana’s **Local Preferred Provider Organization (LPPO)** plans have a significantly higher proportion of **unengaged members** compared to **Health Maintenance Organization (HMO)** plans. These unengaged members do not visit their PCP for preventive care, leading to:  
- Reduced provider touchpoints  
- Lower CMS Star Ratings  
- Incomplete risk documentation  
- Potential loss of bonus premiums that support member benefits  

The goal was to develop a predictive model that identifies **members unlikely to engage in preventive care** and provide actionable recommendations to improve engagement.

## Competition Objectives  
1. **Predict unengaged members** for preventive PCP visits  
2. **Identify key characteristics and behaviors** associated with engagement  
3. **Provide strategies** for Humana to increase engagement

## Data  
- **1.9M members** with ~300 features  
- Data includes **demographics, claims, plan details, tenure, sales detail, medical/pharmacy claims, call center interactions, and web activity**  
- **Lookback period:** 1–3 years of member behavior  

## Approach  
- **Feature Engineering**: Created and selected key features using **mutual information scores, chi-square tests, and Isolation Forest for outlier removal**  
- **Modeling**: Built predictive models (XGBoost, Random Forest) achieving **AUC: 76%**  
- **Insights**: Identified **key drivers of engagement** through data analysis  

## Repository Structure  
```
📂 Humana-Mays-Case-Competition  
 ├── 2024CaseCompetition_Manaswi_Purohit_20241011.csv  # Final predictions  
 ├── Data Dictionary MLP.xlsx  # Data dictionary  
 ├── Mays Humana Case Comp Info Call.pdf  # Competition details  
 ├── holdout-feature-engg-manaswi-20241011.ipynb  # Feature engineering & holdout results  
 ├── huamana-case-competition-sharwari-wo_member_conditions_20241010.ipynb  # Model training & feature engineering  

```

## Results  
- **AUC:** 76%  
- Identified **top features** driving engagement  
- Provided **strategies** to improve PCP engagement  

## Conclusion  
Our work helped identify **at-risk members** and provided **data-driven recommendations** to enhance **preventive care engagement** in Medicare Advantage plans.
