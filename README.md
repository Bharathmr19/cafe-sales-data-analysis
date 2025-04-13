# cafe-sales-data-analysis

This project showcases end-to-end data cleaning and exploratory data analysis (EDA) on a cafe’s transactional sales dataset. Conducted using **Python** in **Jupyter Notebook**, it includes insights that can drive business decisions for cafe operations.

---

## 📁 Project Structure

- `dirty_cafe_sales.csv` - Raw dataset containing inconsistencies and missing values.
- `cleaned_cafe_sales.csv` - Cleaned version after preprocessing.
- `data_cleaning.ipynb` - Jupyter Notebook for cleaning the raw dataset.
- `data_analysis.ipynb` - Jupyter Notebook with EDA, feature engineering, and visualizations.

---

## 🧹 Data Cleaning Highlights

- Handled missing values and incorrect entries (like "Error" and "Unknown").
- Converted appropriate columns to numeric and datetime formats.
- Removed logically invalid records (e.g., zero-priced items with quantity > 0).
- Exported a cleaned dataset for downstream use.

---

## 📊 Exploratory Data Analysis

- **Revenue Trends**: Visualized daily revenue trends.
- **Best-Selling Items**: Identified top-selling and top revenue-generating items.
- **Customer Behavior**: Analyzed payment methods, location preferences, order sizes.
- **Feature Engineering**: Introduced fields like `Revenue Per Item` and `Discount Applied`.
- **Correlation Heatmaps**: Displayed relationships between numerical and categorical variables.

---

## 📌 Key Insights

- Top-selling item: `Salad`
- Highest revenue-generating item: `Salad`
- Most common payment method: `Digital Wallet`
- Most popular sales channel: `In-Store`
- Average order value: **$8.46**

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

---
