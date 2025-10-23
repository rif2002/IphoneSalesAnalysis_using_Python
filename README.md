# iPhone Sales Analysis in India

This project analyzes iPhone sales data from **Flipkart** to uncover trends in **ratings, reviews, pricing, and discounts**. The goal is to identify top-rated iPhones, understand customer preferences, and explore relationships between price, discounts, and number of ratings.

## Dataset
- Source: Kaggle
- Dataset: Dataset: [apple_products.csv](https://github.com/rif2002/IphoneSalesAnalysis_using_Python/blob/main/apple_products.csv)
- Columns include:
  - `Product Name`, `Brand`, `Sale Price`, `Mrp`, `Discount Percentage`
  - `Number Of Ratings`, `Number Of Reviews`, `Star Rating`, `Ram`, `Product URL`
 
## Analysis Objectives / Key Questions

This project addresses the following key questions:

1. What are the top 10 highest-rated iPhones on Flipkart in India?  
2. How many ratings do the highest-rated iPhones on Flipkart have?  
3. Which iPhone has the highest number of reviews on Flipkart?  
4. What is the relationship between the sale price of iPhones and the number of ratings on Flipkart?  
5. What is the relationship between the discount percentage and the number of ratings of iPhones on Flipkart?  
6. Can you figure out the least expensive and most expensive iPhones in the Indian market, along with all their specifications?


## Key Analyses and Insights

### Top-Rated iPhones
- The top 10 highest-rated iPhones were extracted based on star ratings.
- Example: iPhone 11 Pro Max variants are among the highest rated.

### Number of Ratings and Reviews
- Bar charts were created to visualize the **number of ratings** and **number of reviews** for the top-rated iPhones.
- Insight: **Apple iPhone XR** leads in both number of ratings and reviews, indicating high popularity among users.

### Price vs. Ratings
- Scatter plots show a negative linear relationship between **sale price** and **number of ratings**.
- Insight: Lower-priced iPhones tend to receive more ratings, suggesting higher sales volumes.

### Discount Percentage vs. Ratings
- Scatter plots show the relationship between **discount percentage** and **number of ratings**.
- Insight: iPhones with higher discounts generally receive more ratings, showing that discounts influence purchasing behavior.

### Most and Least Expensive iPhones
- **Most Expensive:** iPhone 12 Pro (Silver, 512 GB) – ₹140,900
- **Least Expensive:** iPhone SE (White, 64 GB) – ₹29,999

## Tools and Technologies
- **Python**: Data cleaning, manipulation
- **Pandas & NumPy**: Data processing and aggregation
- **Plotly Express & Graph Objects**: Interactive visualizations

## Conclusion
This analysis provides insights into **customer preferences, pricing strategy, and product popularity** for iPhones in India. It highlights the impact of price and discounts on sales and helps identify which iPhone models are most favored by users.
