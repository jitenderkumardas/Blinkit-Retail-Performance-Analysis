# Blinkit Retail Performance Analysis

This project focuses on building a complete Data Cleaning and Exploratory Data Analysis (EDA) pipeline for retail sales data using Python, Pandas, and Seaborn.

## 🛠️ Data Cleaning Highlights
- **In-place Mutations:** Handled structural changes cleanly without redundant memory copies.
- **Advanced Imputation:** Filled missing values in `Item Weight` using a group-by median transform strategy based on `Item Type`.
- **Data Standardization:** Resolved structural typos in categorical features (e.g., standardizing 'LF', 'low fat' into 'Low Fat').

## 📊 Key Performance Indicators (KPIs) Solved
1. **Sales Optimization:** Aggregated total and mean sales across various outlet types and product categories using pandas `.agg()`.
2. **Inventory Management:** Created custom weight buckets (`Light`, `Medium`, `Heavy`) using `pd.cut()` to identify high-moving stock weights.
3. **Product Visibility Index:** Evaluated the strength and direction of product visibility against sales using the **Correlation Coefficient ($r = -0.0013$)**, concluding an independent relationship.
4. **Store Expansion Strategy:** Analyzed performance metrics across different store tiers and sizes to guide expansion decisions.

## 📈 Tech Stack Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib
