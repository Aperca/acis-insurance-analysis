# Insurance Risk Analytics & Pricing Model

## Overview
This project analyzes insurance claims data to identify risk patterns and support data-driven pricing decisions. It combines statistical analysis and machine learning to better understand how risk varies across different segments and how pricing strategies can be improved.

## Problem
Insurance systems rely on accurate risk assessment, but real-world data often contains hidden patterns, imbalances, and inconsistencies that make pricing decisions difficult.

This project explores how data analysis and predictive modeling can help identify low-risk segments, reduce losses, and improve pricing strategies.

## Approach
- Performed data cleaning and exploratory data analysis (EDA)
- Analyzed claim frequency, severity, and loss ratios across regions
- Applied statistical testing to evaluate differences between groups
- Built predictive models (Random Forest, Gradient Boosting) for premium estimation
- Interpreted model outputs to support decision-making

## Key Findings
- The portfolio shows signs of imbalance, with loss ratios indicating higher payouts than premiums in some segments
- A significant portion of policies have zero premiums, suggesting data or pricing inconsistencies
- Claims are rare but high-impact, creating risk concentration challenges
- Risk varies significantly across geographic regions

## Tech Stack
- Python (Pandas, NumPy, scikit-learn)
- StatsModels, SciPy
- Data visualization (Matplotlib, Seaborn)
- DVC for dataset management

## Results
- Built predictive models to support premium optimization (R² ≈ 0.42)
- Identified key factors influencing insurance risk
- Generated insights for improving pricing strategies and reducing loss ratios

## Impact
This project demonstrates how data-driven approaches can support more reliable and transparent insurance systems by:
- improving risk assessment  
- enabling more consistent pricing decisions  
- supporting data-informed business strategies  

## Limitations
- Model performance depends on dataset quality and feature availability  
- Not designed for real-time or production deployment  

## Future Improvements
- Incorporate larger and more diverse datasets  
- Improve model performance with advanced techniques  
- Develop a deployable decision-support system for pricing
