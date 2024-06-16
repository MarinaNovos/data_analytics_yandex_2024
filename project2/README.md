# Market Research for Public Catering in Moscow

## Project Description
Investors from the fund  have decided to venture into a new field and open a public catering establishment in Moscow. The clients do not yet know what type of establishment it will be: a café, restaurant, pizzeria, pub, or bar, nor do they know the location, menu, and prices. Initially, they request a market study of Moscow to find interesting features and present the results, which will help in choosing a suitable place for the investors.

## Data Description
- **name** — establishment name
- **address** — establishment address
- **category** — establishment category, such as "café", "pizzeria", or "coffee shop"
- **hours** — information on days and hours of operation
- **lat** — latitude of the geographical point where the establishment is located
- **lng** — longitude of the geographical point where the establishment is located
- **rating** — establishment rating according (highest rating is 5.0)
- **price** — price category in the establishment, such as "average", "below average", "above average", etc.
- **avg_bill** — string storing the average order cost as a range
- **middle_avg_bill** — number estimating the average bill
- **middle_coffee_cup** — number estimating the cost of a cup of cappuccino, included only for values in the avg_bill column starting with "Cup of cappuccino”
- **chain** — number expressed as 0 or 1 indicating whether the establishment is part of a chain (for small chains, errors may occur): 0 — not part of a chain, 1 — part of a chain
- **district** — administrative district where the establishment is located, such as the Central Administrative District
- **seats** — number of seats

## Libraries Used
- Pandas
- NumPy
- datetime
- Matplotlib
- Seaborn
- SciPy (Mann-Whitney U test, ANOVA)

## Findings and Recommendations
Analysis of coffee shops presented in the dataset yielded the following conclusions:
- The dataset includes 1,413 coffee shops.
- Most coffee shops are located in the central, northern, and northeastern districts of Moscow. This may indicate a high demand for coffee in these areas or a more favorable business environment for opening coffee establishments.
- Of the 1,413 coffee shops, only 59 operate 24/7. This indicates a demand for 24-hour coffee shops, but they are few in number.
- The average rating of coffee shops is above 4.2 in all administrative districts of Moscow, indicating a fairly high level of service quality. The highest average rating is in the Central Administrative District (4.34), which may indicate high competition and demand for coffee in this area.
- The average cost of a cup of cappuccino in different districts ranges from 151 to 190 rubles. Pricing when opening a new coffee shop should be based on the competitive environment in the area, the target audience, and service costs.
- The average bill in coffee shops can vary significantly depending on the district. For example, coffee shops in the Western Administrative District have higher prices than in other districts, while in the Southeastern Administrative District the average bill is significantly lower. Differences in average bills may be related to the income levels of residents in the area. For instance, in the Western Administrative District, where the average bill is higher, residents likely have higher incomes, allowing coffee shops to set higher prices. In contrast, the Southeastern Administrative District, where the average bill is lower, may have lower income levels, limiting the pricing potential of coffee shops.
- The highest average number of seats is observed in the Western Administrative District, Central Administrative District, and Northwestern Administrative District. The lowest average number of seats is typical for the Southeastern Administrative District, Southwestern Administrative District, and Southeastern Administrative District. Differences in the number of seats may indicate different formats and sizes of coffee establishments in different districts. For example, in the Central and Western Administrative Districts, where the number of seats is higher, there may be more large coffee shops with an extensive range of products and services. In contrast, in the Southeastern and other administrative districts, where the number of seats is lower, smaller coffee shops with a narrow specialization may prevail.

### Analysis of Coffee Shop Distribution in Various Districts of Moscow
- **Central District**:
  - Advantages: Highest number of coffee shops, many 24-hour coffee shops, high ratings, a large number of seats, high average bill, and high cost of a cup of cappuccino. Opening a coffee shop in the central district is recommended due to the high potential of customers, high ratings, and the possibility to attract a diverse audience. However, competition may be high, requiring high-quality service and competitive pricing.
- **Western District**:
  - Advantages: High number of 24-hour coffee shops, highest average number of seats, highest average bill, and highest cost of a cup of cappuccino. This district is recommended for a coffee shop with a unique interior or concept that can attract visitors even at night.
- **Northwestern District**:
  - Advantages: High ratings, average number of seats, and average cost of a cup of cappuccino. This district is suitable for a coffee shop focused on quality coffee and a cozy atmosphere. A small number of coffee shops and competition can ensure a stable flow of customers.
- **Southern District**:
  - Advantages: Average ratings, average number of seats, and low cost of a cup of cappuccino. This district may be suitable for a coffee shop with moderate prices and a wide range of products, attracting a broad audience. The small number of 24-hour coffee shops should be considered.
- **Eastern District**:
  - Advantages: Average ratings, a small number of seats, and average cost of a cup of cappuccino. Potentially suitable for small coffee shops focused on quality coffee and quick service. The small number of 24-hour coffee shops should be considered.
- **Southeastern District**:
  - Disadvantages: Low ratings, lowest average number of seats, low average bill, and low cost of a cup of cappuccino. This district is not recommended for opening a new coffee shop due to the low customer potential and poor performance compared to other districts.
- **Southwestern District**:
  - Advantages: Average ratings, a small number of seats, and high average bill. This district may be interesting for a coffee shop with a unique concept or marketing campaigns. Attention should be given to the small number of 24-hour coffee shops.
- **Northern District**:
  - Advantages: High ratings, average number of seats, and average cost of a cup of cappuccino.
- **Northeastern District**:
  - Disadvantages: Low ratings, average number of seats, and average cost of a cup of cappuccino.
