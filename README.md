# TechStream Solutions - Streamline Pro Unit Economics Analysis

![TechStream Solutions Logo](https://via.placeholder.com/150)

## Overview

This repository contains the unit economics analysis of **Streamline Pro**, a Software as a Service (SaaS) platform by **TechStream Solutions**. Streamline Pro provides comprehensive project management and collaboration tools for businesses of all sizes. Understanding the unit economics of the product helps the company:

- Assess the profitability of acquiring and retaining customers.
- Evaluate the efficiency of marketing and sales strategies.
- Make informed decisions about scaling operations and optimizing resource allocation.

The analysis focuses on the month of **March 2023**.

---

## Data Source

The data used for this analysis is stored in the shared Google Drive folder:

[Google Drive - TechStream Solutions Data](https://drive.google.com/drive/folders/1qhOW9Y2orRXuzbX-kXEmuJ7TMQiRs2Uv?usp=drive_link)

The dataset includes:

- Customer acquisition costs (marketing & sales)
- Revenue per customer
- Operational and service costs
- Customer retention metrics

---

## Objective

The goal of this project is to calculate key unit economics metrics for Streamline Pro:

1. **Customer Acquisition Cost (CAC)**
2. **Average Revenue Per User (ARPU)**
3. **Cost of Goods Sold (COGS)**
4. **Gross Margin**
5. **Customer Lifetime Value (LTV)**
6. **LTV / CAC ratio**

These metrics will provide insight into the profitability and sustainability of Streamline Pro.

---

## Methodology

All calculations were performed using **Python** and **Pandas** in **Google Colab**. The steps included:

1. **Loading the data** from Google Drive into Colab using `pandas`.
2. **Data cleaning and preparation** to ensure accuracy.
3. **Calculation of key metrics**:

   - **CAC (Customer Acquisition Cost)**: Total marketing and sales costs ÷ Number of new customers acquired.
   - **ARPU (Average Revenue Per User)**: Total revenue ÷ Total number of customers.
   - **COGS (Cost of Goods Sold)**: Direct operational costs per customer.
   - **Gross Margin**: `(ARPU - COGS) / ARPU`
   - **LTV (Customer Lifetime Value)**: `ARPU × Average customer lifetime in months`
   - **LTV / CAC ratio**: Evaluates the return on customer acquisition investment.

4. **Visualization** of results (if applicable) using `matplotlib` or `seaborn`.

---

## Key Findings (Example)

| Metric            | Value       |
|------------------ |------------|
| CAC               | $120        |
| ARPU              | $250        |
| COGS              | $80         |
| Gross Margin      | 68%         |
| LTV               | $600        |
| LTV / CAC         | 5.0         |

> These numbers are illustrative. The actual values are calculated in the Colab notebook.

---

## How to Use

1. Open the **Colab Notebook** included in this repo.
2. Run all cells to see calculations based on the raw datasets.
3. Explore the metrics and modify parameters if needed (e.g., different time periods, customer segments).

---

## Colab Notebook

You can view and run the analysis in Google Colab here:

[Streamline Pro Unit Economics Analysis](https://colab.research.google.com/drive/1xcYoUKG_4kJ-_K4yjb2_Rr5A_9iYbetq#scrollTo=KSxQynPsoibS)

---

## Conclusion

The unit economics analysis provides a clear picture of Streamline Pro's financial performance per customer. By understanding CAC, ARPU, COGS, and LTV, TechStream Solutions can:

- Optimize marketing and sales spending.
- Improve customer retention strategies.
- Ensure sustainable growth and maximize profitability.

---

## License

