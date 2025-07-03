# DSA-EXCEL-PROJECT-
Comprehensive Excel project on Amazon case study, including complete dataset, analysis steps, and visualizations with a step-by-step breakdown.

## **Project Topic**: Amazon Product Review Analysis 

### **Project Overview**

#### **Case Study Context**
This project is part of an internship simulation at *RetailTech Insights*, an e-commerce analytics firm. As a Junior Data Analyst, the goal is to analyze Amazon product and customer review data to uncover actionable insights that can guide:

- Product improvement

- Marketing strategies

- Customer engagement

#### **Dataset Description**
The dataset was sourced from Amazon product pages and contains:

- Product Information: Name, category, price, discount, average rating

- Customer Engagement: Review counts, review titles, and content summaries

- Each row represents a unique product, with some fields (e.g. reviews) containing aggregated or comma-separated values.

#### **Analysis Objectives**
Using Excel tools such as Pivot Tables, Conditional Formatting, and Calculated Columns, the project answers the following key business questions:

- Average discount percentage by category

- Product count per category

- Total number of reviews by category

- Top-rated products

- Comparison of average actual price vs. discounted price

- Most reviewed products

- Number of products with ≥50% discount

- Distribution of product ratings (e.g., 3.0, 4.0, etc.)

- Potential revenue by category (actual_price × rating_count)

- Product count by price range: < ₹200, ₹200–₹500, > ₹500

- Relationship between rating and discount

- Products with fewer than 1,000 reviews

- Categories with highest-discounted products

- Top 5 products based on combined rating and review count

#### **Step by Step**
1 Duplicates was removed from the *product_id* to ensure that all I.D is indeed unique

2 The Category column was separated using the *text-to-column* to enable me interact with the categories at an understandable level

3 The figures populated for the *discounted price*, *actual price*, *discounted parcentage*, *rating* and *rating count* was reviewed to confirm that all figures are correctly populated and errors was expunged or corrected

4 The currency stated was inputted in the data set that involves money 

5) The price range bucket column was calculated using the IF and OR function

6) The discount rating of **50% or more** was calculated to answer the question *How many products have a discount of 50% or more?*

7) Total potential revenue by category was calculated using the formular *(actual_price × rating_count)*

8) To calculate the question *How many products have fewer than 1,000 reviews* **the countif function** was used

9) Pivot tables was created for all listed questions

10) Dashboard was created for specific pivot table as related to the earlier insight

#### **Final Task**: *Excel Dashboard*
A clean, interactive Excel dashboard is created based on the insights generated. This includes:

- Interactive slicers and filters

- Visualizations (bar, pie, line charts)

- Below is the cleaned data, pivot table and dashboard

-  [Amazon case study (cleaned).xlsx](https://github.com/user-attachments/files/21040326/Amazon.case.study.cleaned.xlsx)

#### **Tools Used**
1 Microsoft Excel

2 Pivot Tables

3 Formulas (COUNTIF, IF, OR, IFS, etc.)

4 Conditional Formatting


5 Charts and Graphs

6 Dashboard Design



