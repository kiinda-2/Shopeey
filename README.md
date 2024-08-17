# 

### Shopeey - Toy Store

#### This project analyzes sales data to uncover patterns and trends in product performance across different product categories.

###  Objective: Create an annual sales report for 2022, to understand customers and grow more sales in 2023   

## Data Sources
The analysis uses two main data tables:
- Sales table: Contains transaction data including date and unit
- Products table: Contains product information including category and price

## Methodology
1. Data Transformation:
   - Extracted day of week from sales dates
   - Grouped days of week (weekday vs. weekend)
   - Used INDEX-MATCH to retrieve product values
     
2. Visualization:
   - Created charts and graphs to represent sales trends
   - Implemented a slicer for product category filtering

## Key Findings
1. Weekend vs. Weekday Sales:
   - Weekday sales are 23% higher than weekend sales
   - Product category "Electronics" shows the highest sales of 71% in weekday sales compared to other product category

2. Product Category Performance:
   - "Lego bricks, color buds, magic sand " are the top-selling category overall, but Lego bricks account for twice as much as the other two.
   - "Arts & Crafts" shows the highest monthly growth rate, especially between August and September of 2018. 
3. Seasonal Trends:
   - Q4 sales are 40% higher than other quarters, likely due to holiday shopping
  
## Visualizations
###### Store dashboard
![ Store dashboard](https://github.com/user-attachments/assets/7d303b41-af1e-4508-bd3e-635e1a480dbe)   

![Sales by Day of Week](https://github.com/user-attachments/assets/163e8246-7374-423e-99ba-515e77f9c8eb)   

###### Top Sales Product Performance
![ Top Sales Product Performance](https://github.com/user-attachments/assets/9e7158b1-c19e-4493-85ca-08c229d7afa8)   

###### Monthly Performance
![Monthly Performance](https://github.com/user-attachments/assets/e3e0ab7c-6226-44c1-9c9e-0362e6eeb5bc)

  
## Future Work
- Integrate customer demographic data for more detailed analysis
- Develop sales forecasting
