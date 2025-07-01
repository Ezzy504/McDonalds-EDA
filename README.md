# 🍔 McDonald's Nutrition EDA

Exploratory Data Analysis (EDA) of McDonald's menu nutrition dataset using Pandas, SQLite, and Seaborn.

---

## 📁 Project Structure

- `menu.csv`: Raw nutrition dataset from Kaggle
- `mcdonalds.db`: SQLite database version of the dataset
- `eda_mcdonalds.ipynb`: Jupyter notebook with complete analysis

---

## 🔍 Key Insights

- **Highest sodium** item: Chicken McNuggets (40 pieces) – 3600 mg
- Strong **positive correlation** between protein and total fat (r ≈ 0.81)
- Identified **sugar outliers** above 120g in some food items

---

## 📊 Visualizations

- Swarm plot (Sodium by category)
- Joint plot (Protein vs Total Fat)
- Box plot (Sugar distribution with outliers)

---

## 🚀 How to Run

1. Clone the repo or download files
2. Install required Python libraries:
```bash
pip install pandas matplotlib seaborn
