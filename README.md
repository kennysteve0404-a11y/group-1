# Superstore Sales — End-to-End EDA Project

A complete Exploratory Data Analysis project on the Superstore Sales dataset, covering data ingestion, investigation, cleaning, EDA, and preprocessing for machine learning.

---

## Project Overview

This project performs a full end-to-end EDA on a US retail superstore dataset containing 9,994 orders placed between 2012 and 2015. The analysis investigates sales performance, profitability, customer segments, regional trends, and the impact of discounting — culminating in a clean, ML-ready dataset.

Completed as part of a Machine Learning course assignment focused on the business and commercial sector.

---

## Dataset

- **Name:** Superstore Sales Dataset
- **Source:** [Kaggle — vivek468/superstore-dataset-final](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Records:** 9,994 orders
- **Features:** 21 columns
- **Period:** January 2012 — December 2015
- **Domain:** US Retail / Commercial Business

---

## Project Structure

```
superstore-eda/
│
├── superstore_eda.ipynb       # Main Jupyter Notebook
├── Superstore.csv             # Local dataset (or loaded via KaggleHub)
├── README.md                  # Project documentation
```

---

## Pipeline

1. Data Ingestion
2. Data Investigation
3. Data Cleaning and Feature Engineering
4. Exploratory Data Analysis
5. Preprocessing for ML
6. Business Summary

---

## How to Run

**1. Clone the repository**
```bash
git clone https://github.com/your-username/superstore-eda.git
cd superstore-eda
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub jupyter
```

**3. Launch Jupyter Notebook**
```bash
jupyter notebook
```

**4. Open `superstore_eda.ipynb` and run all cells top to bottom.**

The dataset will be pulled automatically via KaggleHub, or place `Superstore.csv` in the same directory for local loading.

---

## Key Findings

- Approximately 30% of orders are loss-making, primarily driven by discounts above 40%
- Technology is the most profitable category; Furniture consistently underperforms
- Sales and Profit grew year over year from 2012 to 2015
- Strong Q4 seasonality — November and December are peak sales months
- Discount and Profit are negatively correlated

---

## Technologies Used

- Python 3, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- KaggleHub
- Jupyter Notebook

---

## Author

Group3 — Machine Learning Course, Business and Commercial Sector EDA Project

---

## License

This project is for educational purposes. Dataset credit goes to the original publisher on [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final).
