# Data Analysis of Home Goods Online Store 
## Project Description
The goal is to identify customer profiles and conduct a comprehensive analysis of the product assortment. The resulting customer profiles will be used by the marketing department to send special offers. Specifically, we need to determine which segments of customers buy frequently, in large quantities, and at high prices, and which segments may not be worth targeting with offers. Understanding when, to whom, and from which product categories to send offers is also crucial.

## Data Description
- **date** — order date
- **customer_id** — customer identifier
- **order_id** — order identifier
- **product** — product name
- **quantity** — quantity of product in the order
- **price** — product price

## Libraries Used
- Pandas
- NumPy
- datetime
- Matplotlib
- Seaborn
- SciPy (Mann-Whitney U test, ANOVA)

## Findings and Recommendations
Data analysis on the distribution of orders by months, days of the week, and product categories revealed key trends. The period from February to April shows the highest customer activity, possibly related to seasonal factors or marketing campaigns. Saturday has the lowest number of orders, while Tuesday is the busiest day. Flowers and seedlings are the most popular product categories, whereas bags and accessories, despite fewer orders, generate significant revenue.
Customer segmentation based on RFM analysis identified various groups, from "Champions" (active and loyal customers) to "Inactive" (those who have made few purchases for a long time). Analysis of the average check confirmed differences in purchasing behavior between user categories, especially between "Champions" and "Regular Customers". However, ANOVA analysis of purchase structure did not show statistically significant differences between user categories, indicating similar product category preferences across segments.
These findings can be used to optimize marketing strategies and manage the product assortment in the online store.
### Personalized Recommendations for Customer Categories:
- **Champions**: Reward their loyalty with exclusive offers. Engage them with new products and initiatives as they can become brand ambassadors.
- **Regular Customers**: Continue to stimulate their purchases by offering higher-tier products or attractive promotions. Encourage them to leave reviews and participate in loyalty programs.
- **Potential Loyalists**: Offer the benefits of joining the loyalty program and recommend additional products that may interest them.
- **New Customers**: Maintain contact through personalized mailings and attractive offers to encourage more frequent purchases.
- **Promising**: Increase brand awareness and offer trial versions or discounts to solidify their interest.
- **Customers Needing Attention**: Actively engage them with limited-time offers and personalized product selections.
- **At Risk of Churning**: Personalize your offers to win them back by offering discounts and additional benefits for loyal customers.
- **Cannot Lose Them**: Offer unique advantages, such as VIP status or exclusive offers, to retain them.
- **Hibernating**: Rekindle their interest with special offers or discounts to draw them back to active shopping.
- **Lost**: Depending on their potential value, decide whether to restore contact with them or focus on other customer segments.
