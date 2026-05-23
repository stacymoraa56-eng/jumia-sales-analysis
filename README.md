#  Jumia Product Performance Dashboard (Excel)

This project presents an interactive Excel dashboard analyzing product performance data from Jumia. The analysis explores how pricing, discounts, ratings, and customer reviews influence customer engagement in an e-commerce environment.

The project demonstrates data cleaning, transformation, exploratory analysis, dashboard design, and analytical storytelling using Excel/WPS Spreadsheet.

---

#  Project Objectives

The objective of this project was to:

- Analyze product pricing and discount patterns
- Evaluate customer engagement through reviews and ratings
- Identify top-performing and underperforming products
- Build an interactive dashboard for business decision-making
- Generate actionable recommendations from product performance trends

---

#  Data Cleaning & Preparation

Several data quality issues were identified and resolved during preprocessing:

- Removed duplicate product entries
- Converted negative review values into positive values
- Converted `Current Price` and `Old Price` columns into numeric format
- Removed currency symbols (`KSh`) and commas
- Converted discount percentages into numeric values
- Extracted numeric ratings from text-based rating fields
- Addressed missing values in the Reviews and Rating columns
- Standardized formatting across columns

---

#  Feature Engineering

Additional analytical columns were created to improve analysis:

## Added Columns

- **Discount Amount**
  - `Old Price - Current Price`

- **Rating Category**
  - Poor → Ratings below 3
  - Average → Ratings between 3 and 4.4
  - Excellent → Ratings 4.5 and above

- **Discount Category**
  - Low Discount → Below 20%
  - Medium Discount → Between 20% and 40%
  - High Discount → Above 40%

---

#  Analysis Performed

## Descriptive Analysis

The project analyzed:

- Average current price
- Average old price
- Average discount percentage
- Average product rating
- Most expensive and least expensive products
- Product distribution across rating categories
- Product distribution across discount categories

---

##  Trend & Relationship Analysis

The following relationships were explored:

- Discount percentage vs number of reviews
- Rating vs number of reviews
- Whether higher discounts increase customer engagement
- Whether highly rated products attract more reviews

Scatter plots and pivot charts were used to visualize these relationships.

---

##  Product Performance Analysis

The dashboard identifies:

- Top 10 products with the highest discounts
- Top 10 products with the most reviews
- Top-rated products
- Lowest-rated products
- Comparison between high-discount and low-discount products

---

#  Dashboard Features

The interactive dashboard contains the following sections:

## Overview KPIs

- Total Products
- Average Rating
- Average Discount Percentage
- Total Reviews

---

## Product Performance Visuals

- Top products by rating
- Top products by reviews
- Top products by discount percentage

---

## Trend Analysis Visuals

- Discount vs Reviews scatter plot
- Rating vs Reviews scatter plot

---

## Product Category Analysis

- Rating category distribution
- Discount category distribution

---

## Interactivity

The dashboard includes slicers/filters for:

- Rating Category
- Discount Category
- Price Range

---

#  Key Insights

- Higher discounts show only a weak relationship with customer engagement
- Higher-rated products tend to attract more reviews
- Customer satisfaction appears to influence engagement more strongly than discounts
- A small number of products dominate customer interaction
- High discounts do not always correspond to high product ratings
- Medium-discount products generated stronger engagement compared to extremely discounted products

---

#  Recommendations

Based on the findings from the analysis, the following recommendations are proposed:

- Prioritize product quality and customer satisfaction improvements
- Use discounts strategically instead of aggressively
- Promote highly rated products with strong customer interaction
- Monitor low-rated products for potential quality issues
- Encourage customer reviews to improve visibility and trust
- Balance discount strategies with customer experience improvements

---

#  Tools Used

- Excel 
- Pivot Tables
- Pivot Charts
- Scatter Plots
- Data Cleaning & Transformation
- Conditional Formatting
- Dashboard Design

---

#  Dashboard Preview
![Dashboard Preview](https://github.com/stacymoraa56-eng/jumia-sales-analysis/blob/main/Jumia%20Sales%20Analysis%20Dashboard%20.png)

---

# 📌 Conclusion

This project demonstrates practical Excel-based business analytics skills, including:

- Data cleaning
- Data transformation
- Exploratory data analysis
- Dashboard development
- Insight generation
- Business recommendation development

The dashboard provides actionable insights that can support pricing strategy, customer engagement, and product positioning decisions in an e-commerce environment.
