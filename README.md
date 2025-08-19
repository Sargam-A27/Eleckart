**📊 Capstone Project – ElecKart (Market Mix Modeling)**

This project focuses on building a Market Mix Model (MMM) for ElecKart, an e-commerce platform. The goal is to analyze the impact of various marketing levers (discounts, advertisements, sponsorships, etc.) on sales performance and recommend the optimal budget allocation to maximize revenue and profitability.

The analysis is conducted across three product sub-categories:

📷 Camera Accessories

🎵 Home Audio

🎮 Gaming Accessories

**🎯 Business Objective**

Understand the effect of marketing spends and discounts on sales.

Identify the most effective marketing channels and sales drivers.

Recommend the optimal marketing budget allocation for the upcoming year.

**⚙️ Data & Methodology**

_🔹Data Cleaning & Preprocessing_

Handling missing values & inconsistent data.

Standardizing data types for analysis.

Removing outliers where necessary.

_🔹 Feature Engineering_
Created features like holiday flags, special sales flags, payday effects, and discount categories.

Engineered lag variables for demand patterns.

_🔹 Exploratory Data Analysis (EDA)_

📈 Trend analysis of revenue, sales volume, and discount impact.

🛒 Sub-category level insights (Camera, Home Audio, Gaming).

🔍 Correlation analysis of variables (e.g., discounts, ad spend, sales).

🎉 Special event & seasonal impact analysis.

**📊 Key Insights**

Home Audio drives maximum COD revenue, while Camera Accessories dominate prepaid orders.

Week 42 (October) shows peak sales due to festive season promotions.

Median revenue is highest at 10–20% discount levels (beyond which profitability declines despite higher sales).

Sponsorships and online ads received the highest ad spend but require optimization.

Luxury products maintain exclusivity by offering minimal discounts compared to mass-market items.

**🤖 Modeling Approach**

Built Market Mix Models (MMM) for each sub-category.

Evaluated impact of ad spend, discounts, special events, and seasonality.

Compared results across categories to optimize allocation.

**✅ Recommendations**

Maintain 10–20% discounting strategy for optimal profitability.

Reallocate ad budget to more effective channels (balance sponsorships with digital ads).

Increase focus on festive season campaigns (Oct–Nov) to maximize returns.

Improve customer experience with better website UI and product assortment (identified in flowchart analysis).

_📂 Repository Structure_
├── Capstone_Project Final.ipynb     # Jupyter Notebook with full analysis
├── Capstone Project Ecommerce - Eleckart.pptx  # Project presentation
├── FlowChat.pdf                     # Flowchart of business problems
├── SPIN selling framework.xlsx      # Supporting marketing framework
├── Marketing Mix Analysis Video.mp4 # Video presentation/explainer
└── README.md                        # Project documentation

**_🛠️ Tools & Libraries_**

Python (Pandas, NumPy, Scikit-learn, Statsmodels, Matplotlib, Seaborn)

Jupyter Notebook

Excel (for SPIN framework)
