# 📊 Superstore Sales - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a retail "Superstore" dataset to uncover insights about sales, profits, and discounts across different product categories and months.

## 🛠️ Tech Stack
*   **Programming Language:** Python
*   **Data Manipulation:** Pandas, NumPy
*   **Data Visualization:** Matplotlib, Seaborn
*   **Environment:** Jupyter Notebook (VS Code)

## 🔍 Key Questions Answered
1.  Which product sub-categories generate the highest and lowest profits?
2.  How do discounts affect the profit margin?
3.  What is the trend of profit margin across different months of the year?

## 📈 Key Insights (Results)
*   **Loss-Making Categories:** The "Tables" sub-category generates high sales but operates at a significant loss due to high average discounts (~26%).
*   **Seasonality:** The highest profit margins occur in **February** and **October**, while **April** and **July** show the lowest margins.
*   **Discount Impact:** High discounts directly correlate with lower profitability in specific categories.

## 📂 Project Structure
*   `notebooks/analysis.ipynb`: The Jupyter Notebook containing all the data cleaning, analysis, and visualizations.
*   `Sample - Superstore.csv`: The raw dataset.
*   `images/`: Contains the generated charts and plots.

## 🚀 How to Run
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt