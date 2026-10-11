# Sample Superstore Sales Analysis

## Project Overview

This project analyzes the Sample Superstore dataset using Python and
Pandas to understand sales performance, profitability, customer
behavior, regional performance, discount impact, and sales trends over
time.

## Objectives

-   Understand and validate the dataset.
-   Calculate total sales, profit, and quantity sold.
-   Compare performance by product, category, sub-category, region,
    state, and customer segment.
-   Identify loss-making products and sub-categories.
-   Explore discounts and their relationship with profitability.
-   Analyze annual and monthly sales trends.
-   Develop practical business recommendations.

## Tools and Libraries

-   Python
-   Jupyter Notebook
-   Pandas
-   NumPy
-   Matplotlib

## Dataset

The CSV contains **9,994 rows and 21 columns**, including order dates,
ship dates, customers, regions, product categories, sales, quantity,
discount, and profit.

## Key Findings

-   **Total sales:** approximately **₹20.22 crore**
-   **Total profit:** approximately **₹2.52 crore**
-   **Total quantity sold:** 37,873 units
-   **Overall profit margin:** 12.47%
-   **Unique customers:** 793
-   **Unique orders:** 5,009
-   **Top category by sales and profit:** Technology
-   **Top region by sales and profit:** West
-   **Lowest regional profit margin:** Central
-   **Highest-profit customer segment by total profit:** Consumer
-   **Loss-making sub-categories:** Tables, Bookcases, and Supplies
-   **Best annual performance:** 2017, the highest-sales and
    highest-profit year in the dataset

> **Currency note:** The source dataset's monetary values are treated as
> US dollars. INR figures above are approximate conversions using ₹88
> per US\$1, not the original values in the CSV. Exchange rates vary.

## Analysis Performed

1.  **Data understanding and cleaning** --- inspected columns and data
    types, checked missing values and duplicate rows, and converted date
    columns to datetime.
2.  **Sales performance** --- compared sales by product, category,
    state, and region; identified high-sales orders and products.
3.  **Profit and discount analysis** --- reviewed negative-profit
    products, loss-making sub-categories, profit margins, and discount
    patterns.
4.  **Customer analysis** --- compared customers and segments by sales
    and profit.
5.  **Time-based analysis** --- summarized annual and monthly sales,
    examined monthly changes, and calculated shipping duration.
6.  **Business recommendations** --- highlighted opportunities to review
    discount policies, improve regional profitability, and plan around
    sales trends.

## Business Recommendations

-   Review pricing and discount strategies for loss-making products,
    especially Tables, Bookcases, and Supplies.
-   Investigate the Central region's lower profit margin.
-   Continue to understand and support strong-performing categories,
    regions, and customer segments.
-   Use monthly sales patterns to inform inventory and marketing plans.
-   Monitor profit margin alongside revenue growth; higher sales do not
    always mean higher profitability.

## How to Run

1.  Download or clone this project repository.

2.  Keep `code.ipynb` and `Sample_Superstore.csv` in the same folder.

3.  Install the required libraries if needed:

    ``` bash
    pip install pandas numpy matplotlib jupyter
    ```

4.  Open Jupyter Notebook and run the notebook cells in order.

## Project Files

-   `code.ipynb` --- analysis notebook.
-   `Sample_Superstore.csv` --- input dataset (use the dataset filename
    referenced in the notebook, or update the read path to match your
    local filename).

## Conclusion

This project demonstrates practical data analysis with Pandas, from data
validation and aggregation to business insight generation. The main
opportunity is to improve profitability through better discount and
pricing decisions while building on the performance of strong categories
and regions.
