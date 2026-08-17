# 🚚 Supply Chain Analysis & Late Delivery Risk Prediction

## 📌 Project Overview

This project performs an end-to-end analysis of supply chain data using Python and Jupyter Notebook.

The analysis focuses on delivery performance, delays, profitability, bottleneck detection, root-cause analysis, time-based patterns, and late-delivery risk prediction using Random Forest.

## 🎯 Objectives

- Understand supply-chain performance
- Analyze delivery delays and shipping behavior
- Measure profitability
- Study the relationship between delivery delay and profit
- Identify potential bottlenecks and root causes
- Analyze delay patterns by month, day, and hour
- Build a machine-learning model for late-delivery risk prediction

## 📊 Dataset

The original dataset contains:

- **180,519 rows**
- **53 columns**
- **0 duplicate records**

Important fields include delivery status, late-delivery risk, category, customer segment, market, order dates, sales, order profit, region, product information, and shipping mode.

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Random Forest Classifier

## 🔄 Project Workflow

```text
Raw Dataset
    ↓
Data Understanding
    ↓
Data Cleaning
    ↓
Feature Engineering
    ↓
Exploratory Data Analysis
    ↓
Business KPI Analysis
    ↓
Profitability Analysis
    ↓
Delivery Delay Analysis
    ↓
Bottleneck Detection
    ↓
Root Cause Analysis
    ↓
Time-Based Analysis
    ↓
Random Forest Model
    ↓
Late Delivery Risk Prediction
    ↓
Business Recommendations
```

## 📈 Key Business KPIs

| KPI | Result |
|---|---:|
| Total Orders | 180,519 |
| Late Deliveries | 13,807 |
| On-Time Delivery | 92.4% |
| Late Delivery | 7.6% |
| 90th Percentile Delay | 3 days |
| Total Profit | $7.9M |

## 💰 Profitability Analysis

Orders are classified into Profit, Loss, and Break-even categories using `Order Profit Per Order`.

The project also compares profitability across different delivery-delay levels.

## 🚚 Delivery Delay Analysis

The analysis calculates delay using actual versus scheduled shipping time and creates an `Is_Delayed` indicator.

The notebook identifies **13,807 delayed records**, representing **7.6%** of the analyzed records.

## 🔍 Bottleneck & Root Cause Analysis

The project includes dedicated analysis sections for:

- Bottleneck detection
- Regional investigation
- Root-cause analysis
- Delay drivers

These analyses help identify areas that may require operational improvement.

## 📅 Time-Based Analysis

Delay percentages are analyzed by:

- Month
- Day of week
- Hour

This helps identify periods where additional operational attention may be required.

## 🤖 Machine Learning

### Late Delivery Risk Prediction

A **Random Forest Classifier** is used to predict late-delivery risk.

| Metric | Score |
|---|---:|
| Accuracy | 72% |
| Precision | 78% |
| Recall | 69% |

## 📌 Key Findings

- The dataset contains 180,519 supply-chain records.
- There are no duplicate records in the original dataset.
- 13,807 records are identified as delayed.
- The calculated on-time delivery rate is 92.4%.
- Standard Class is the most frequently used shipping mode.
- Consumer is the largest customer segment.
- Profitability varies across different delay levels.
- Time-based analysis can reveal higher-risk operational periods.
- The Random Forest model provides a 72% accuracy baseline for late-delivery risk prediction.

## 💡 Business Recommendations

1. Monitor delayed orders proactively.
2. Investigate categories and regions with higher delay rates.
3. Compare shipping-mode performance.
4. Use time-based delay patterns for capacity and staffing planning.
5. Improve the late-delivery prediction model with additional validated features and tuning.
6. Monitor delivery performance together with profitability.

## 📸 Project Visualizations

Add the charts from the `images/` folder here after uploading them to GitHub.

Example:

```markdown
![Supply Chain Analysis](images/analysis_chart_1.png)
```

## 📁 Repository Structure

```text
Supply-Chain-Analysis/
│
├── data/
│   └── DataCoSupplyChainDataset.csv
│
├── notebooks/
│   └── Supply Chain Complete Analysis.ipynb
│
├── images/
│   ├── analysis_chart_1.png
│   ├── analysis_chart_2.png
│   └── ...
│
├── report/
│   └── Supply_Chain_Analysis_Project_Report.docx
│
├── README.md
└── requirements.txt
```

## 🎓 Skills Demonstrated

Python • Pandas • NumPy • Data Cleaning • EDA • Data Visualization • Feature Engineering • KPI Analysis • Supply Chain Analytics • Root Cause Analysis • Bottleneck Analysis • Machine Learning • Random Forest • Model Evaluation

## 👨‍💻 Author

**Prince Panchal**

Data Analytics Portfolio Project
