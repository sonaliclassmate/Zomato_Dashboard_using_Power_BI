# Zomato Business Analytics Dashboard

## Project Overview

This Power BI dashboard offers a comprehensive analysis of Zomato's operational and sales data, focusing on key performance indicators, user demographics, and city-level sales distribution. The analysis is structured across four main pages to facilitate detailed exploration of the business metrics.

The project entry point is the **Index Page**, featuring the Zomato logo and a button leading directly to the Dashboard.

## Dashboard Structure and Key Findings

The dashboard is organised into the following pages:

### 1. Overview (Dashboard)

This page provides the primary high-level summary of the entire dataset:

*   **Total Performance:** Key figures include **987M Amount**, **2M Quantity**, **148K Rating**, and **150K Orders**.
*   **Top Performing City:** Tirupati registered the highest amount among the **Top 5 city Amount** analysis.
*   **Sales by Year:** Sales peaked at **0.41bn in 2018**, followed by decreases in subsequent years (0.34bn in 2019 and 0.14bn in 2020).
*   **Food Category Sales:** The dashboard breaks down sales by food type, showing **Veg (122M)** and **Non Veg (106M)** as the dominant categories, along with **Other (24M)** sales.

### 2. User Performance

This page focuses specifically on customer activity, engagement, and demographics:

*   **Active Users:** The system tracks **78K Active Users** and a total **UserCount of 78K**.
*   **User Dynamics:** The analysis reveals a net loss in the user base, showing **12K Gain Users** compared to **33K Lost Users**.
    *   *Gain Users:* 6.5K Male, 5.1K Female.
    *   *Lost Users:* 18.8K Male, 14.0K Female.
*   **Users by Age:** A detailed bar chart illustrates the distribution of users across different age groups.

### 3. City Overview

The final section focuses on geographical performance metrics, repeating the overall metrics (987M Amount, 2M Quantity, 148K Rating, 150K Orders).

*   **City-Specific Metrics:** Data is presented for key locations, including Electronic City: Bangalore, Old Gurgaon, and Gorakhpur.
*   **Detailed City Table:** This table provides specific values for Sales, Orders, Gain Users, and Lost Users for each city listed. For example, Electronic City: Bangalore shows Sales of 364574, 1039 Orders, 213 Gain Users, and 323 Lost Users.
*   **Visual Analysis:** Supporting visualisations show comparative data for `sale_value by city`, `Count of rating_count by city`, and `ActiveUser by city`.