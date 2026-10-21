# Business Observations

## 1. Regional Performance

- The **West region** generated the highest sales of approximately **$725,457.82** and the highest profit of approximately **$108,418.45**.
- The **East region** generated approximately **$678,781.24** in sales and **$91,522.78** in profit.
- The **Central region** generated approximately **$501,239.89** in sales and **$39,706.36** in profit.
- The **South region** had the lowest sales at approximately **$391,721.91**, while generating approximately **$46,749.43** in profit.
- West and East are the strongest contributors to overall business performance.

## 2. Product and Sub-Category Performance

- **Chairs** recorded the highest sales among the displayed sub-categories, with approximately **$328,449.10** in sales.
- **Copiers** generated the highest profit among the displayed sub-categories, with approximately **$55,617.82**.
- **Accessories** generated approximately **$167,380.32** in sales and **$41,936.64** in profit.
- **Bookcases** require attention because they generated approximately **$114,880.00** in sales but resulted in a **loss of $3,472.56**.
- High sales do not always translate into high profitability.

## 3. Customer Performance

- **Sean Miller** generated approximately **$25,043.05** in sales but a **loss of approximately $1,980.74**.
- **Tamara Chand** generated approximately **$19,052.22** in sales and **$8,981.32** in profit.
- Raymond Buch, Adrian Barton, Sanjit Chand, and Hunter Lopez also showed strong sales and positive profits.
- Customer sales volume and customer profitability can differ significantly.

## 4. Sales Trend

- Monthly sales were analyzed using the `Year-Month` field created from the order date.
- Sales showed noticeable month-to-month variation.
- Sales increased from approximately **$4,519.89 in February 2015** to approximately **$55,691.01 in March 2015**.
- This variation indicates that monthly or seasonal sales patterns may be useful for planning and forecasting.

## 5. Discount and Profitability

- Discount values ranged from **0% to 80%**.
- Some transactions had high sales but low or negative profit.
- One sample transaction with approximately **$957.58 in sales and a 45% discount resulted in a loss of approximately $383.03**.
- Excessive discounting can negatively affect profitability and should be monitored.

## 6. Data Quality Observation

- The original dataset contained **10,800 rows and 21 columns**.
- Several columns contained missing values, including **806 missing values in most business-related columns** and **817 missing values in Postal Code**.
- Missing values were handled by filling categorical values with `"Unknown"` and numerical values with their median.
- Duplicate records were removed before further analysis.
- After processing, there were no remaining missing values.

## 7. Key Business Insights

1. **West is the strongest region** in terms of both sales and profit.
2. **Chairs have high sales**, while **Copiers generate particularly strong profit**.
3. **Bookcases are a potential problem area** because they generate negative profit despite significant sales.
4. Some high-value customers are **not necessarily profitable**, as demonstrated by Sean Miller.
5. **Discount management is important** because high discounts can lead to negative profits.
6. Monthly sales show significant variation, creating opportunities for **sales planning and forecasting**.
7. Business decisions should consider **sales revenue, profitability, discounts, customers, and regional performance** together.

## 8. Business Recommendations

- Focus marketing and sales efforts on the **West and East regions**.
- Review pricing and discount strategies for **loss-making products such as Bookcases**.
- Identify and retain **high-profit customers**, rather than focusing only on high-sales customers.
- Monitor customers with **high sales but negative profit** and review their discount levels and product mix.
- Use monthly sales trends to improve **inventory planning, promotions, and sales forecasting**.
- Maintain regular data-quality checks to ensure missing or duplicate records do not affect business decisions.

## Conclusion

The analysis provides insights into **regional, product, customer, sales-trend, and profitability performance**. The key observation is that **sales volume alone is not enough to measure business success**. Profitability, discount levels, customer value, and regional performance should also be considered when making business decisions.
