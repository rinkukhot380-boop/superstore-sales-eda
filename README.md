# Superstore Sales — Exploratory Data Analysis

Exploratory data analysis on retail sales data to uncover which product categories drive revenue vs. profit, how discounting affects margins, and regional/yearly sales trends.

## Dataset
- **Source:** [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Rows:** ~9,994 orders | **Time range:** 2014–2017
- **Columns used:** Order Date, Ship Date, Region, Category, Sub-Category, Sales, Quantity, Discount, Profit

## Questions Explored
1. Which category generates the most sales?
2. Which category is actually the most *profitable* — and does that match #1?
3. Does discounting hurt profit, and at what point?
4. Which region has the highest total sales?
5. Is the business growing year over year?

## Key Insights
- **Technology** leads in both total sales and total profit — the strongest-performing category on both fronts.
- **Furniture** has the second-highest sales but by far the *lowest* profit of the three categories — high revenue doesn't mean high margin.
- **Discounts above ~20%** consistently push average profit negative; profit stays positive up to that point, then declines sharply as discount increases further.
- **West** is the top-performing region by total sales, ahead of East, Central, and South.
- Sales **dipped slightly in 2015** (–2.8% vs. 2014), then grew strongly through 2016 and 2017 — though the year-over-year growth *rate* actually slowed slightly each year rather than accelerating.

## Tools Used
Python · Pandas · Matplotlib · Seaborn

## How to Run
```bash
pip install pandas matplotlib seaborn
jupyter notebook superstore_eda.ipynb
```
(Download `superstore.csv` from the Kaggle link above and place it in the same folder first.)
