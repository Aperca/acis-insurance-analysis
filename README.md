# ACIS Insurance Analytics Project

## 📊 Project Overview
Comprehensive analysis of insurance claim data for AlphaCare Insurance Solutions to optimize marketing strategy and identify low-risk targets for premium reduction.

### 🎯 Business Objectives
1. Analyze historical insurance claim data (Feb 2014 - Aug 2015)
2. Identify "low-risk" targets for premium reduction
3. Develop predictive models for optimal premium pricing
4. Provide data-driven recommendations for marketing strategy

## 📁 Project Structure
acis-insurance-analysis/
├── data/
│ ├── raw/ # Original data (managed by DVC)
│ └── processed/ # Cleaned and transformed data
├── notebooks/
│ ├── 01_basic_eda.ipynb # Exploratory Data Analysis
│ ├── 02_hypothesis_testing.ipynb # A/B Testing
│ └── 03_machine_learning.ipynb # ML Models
├── scripts/
│ ├── 01_eda_basic.py # EDA scripts
│ └── create_pdf.py # Report generation
├── reports/
│ ├── figures/ # Visualizations
│ ├── final/ # Final reports (PDF & Markdown)
│ └── *.png # Analysis charts
├── requirements.txt # Python dependencies
├── .gitignore # Git ignore rules
└── README.md # This file

text

## 🚀 Key Findings

### 🔍 Critical Business Insights
1. **Portfolio is unprofitable**: Loss Ratio = 1.048 (paying out more than earning)
2. **Major revenue leak**: 38% of policies (381,634) have zero premium
3. **Rare but catastrophic claims**: 99.6% policies have zero claims, but when claims occur, they average 82x the premium
4. **Geographic risk variations**: Significant differences across provinces and zipcodes

### 📈 Statistical Results
- **Highest risk province**: Gauteng (LR = 1.163)
- **Lowest risk province**: Northern Cape (LR = 0.283)
- **High-risk zipcodes**: 302, 1863, 1022 (Loss Ratio > 70)
- **ML Model Performance**: Gradient Boosting achieved R² = 0.425 for premium prediction

## 🛠️ Technologies Used
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Data Version Control**: DVC for large dataset management
- **Statistical Analysis**: SciPy, StatsModels
- **Visualization**: Plotly, Seaborn
- **Version Control**: Git, GitHub

## 📋 Tasks Completed

### ✅ Task 1: Git & EDA
- Created GitHub repository with proper branching
- Performed comprehensive Exploratory Data Analysis
- Created 3+ creative visualizations
- Identified data quality issues and outliers

### ✅ Task 2: Data Version Control (DVC)
- Installed and configured DVC
- Set up local remote storage
- Added 504MB insurance data to DVC tracking
- Established reproducible data pipeline

### ✅ Task 3: A/B Testing & Machine Learning
- **Hypothesis Testing**: Tested 4 key hypotheses about risk differences
- **Statistical Modeling**: Linear regression per zipcode
- **Machine Learning**: Random Forest and Gradient Boosting models
- **Premium Optimization**: Developed model to suggest optimal premiums

### ✅ Task 4: Final Report
- Created Medium-style narrative report
- Generated professional PDF documentation
- Provided actionable business recommendations
- Prepared executive summary

## 📄 Reports Generated
1. **Medium-Style Article**: `reports/final/acis_insurance_report.pdf`
2. **Technical Report**: `reports/final/acis_insurance_analysis_report.md`
3. **Executive Summary**: `reports/final/executive_summary.md`

## 🚀 Getting Started

### Prerequisites
```bash
python>=3.8
pip install -r requirements.txt
Installation
bash
# Clone repository
git clone https://github.com/Aperca/acis-insurance-analysis.git
cd acis-insurance-analysis

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up DVC (for data management)
dvc pull  # Downloads the data from DVC remote
Running Analysis
python
# Open Jupyter notebooks
jupyter notebook notebooks/

# Or run specific scripts
python scripts/01_eda_basic.py
python scripts/create_pdf.py
📊 Key Visualizations
Loss Ratio by Province

Claim Distribution Analysis

Geographic Risk Heatmaps

Feature Importance Charts

Premium Adjustment Recommendations

💡 Business Recommendations
Immediate: Audit and fix zero-premium policies

Short-term: Implement risk-based pricing adjustments

Medium-term: Develop geographic pricing tiers

Long-term: Build real-time pricing engine with ML

📈 Expected Impact
Loss Ratio Improvement: 1.048 → 0.85 (19% improvement)

Revenue Leakage Reduction: 38% → 5%

Customer Acquisition: +15% through targeted pricing


Repository: https://github.com/Aperca/acis-insurance-analysis
Last Updated: $(date +"%Y-%m-%d")
