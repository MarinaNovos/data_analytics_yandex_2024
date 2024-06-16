# Data Analysis of Internet Store "E-commerce Revenue Optimization"

## Project Description
This project focuses on data analysis for an internet store aimed at optimizing revenue through hypothesis prioritization, A/B testing, and result analysis. The marketing department has provided a list of hypotheses for revenue increase, and the goal is to prioritize these hypotheses, conduct A/B testing, and analyze the outcomes.

## Data Description
The project utilizes the following datasets:
- **hypothesis.csv**: Contains hypotheses with attributes:
  - Hypothesis: Brief description of the hypothesis.
  - Reach: User reach score on a 10-point scale.
  - Impact: Impact on users on a 10-point scale.
  - Confidence: Confidence in the hypothesis validity on a 10-point scale.
  - Efforts: Resources required to test the hypothesis on a 10-point scale.

- **orders.csv**: Includes order details:
  - transactionId: Order identifier.
  - visitorId: User identifier placing the order.
  - date: Order date.
  - revenue: Order revenue.
  - group: A/B test group designation.

- **visitors.csv**: Tracks daily visitors:
  - date: Date of observation.
  - group: A/B test group.
  - visitors: Number of users on the given date and group.

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- SciPy (stats module)

## Findings and Recommendations
Based on the A/B test analysis, the following conclusions and decisions were made:
- Group B showed a significant improvement in the average number of orders per visitor compared to Group A, both in raw and cleaned data. This change is statistically significant and likely due to implemented changes.
- There were no statistically significant differences in average order size between groups, indicating initial differences observed were likely due to anomalies.
- Group B demonstrated increases in cumulative revenue and average order size compared to Group A, albeit with fluctuations possibly influenced by anomalies or natural variability.
- Changes in cumulative average orders per visitor stabilized towards the end of the test, while cumulative average order sizes exhibited significant fluctuations, suggesting the need for anomaly detection and possible correction.
Considering the significant improvement in average orders per visitor in Group B and the absence of statistically significant differences in average order size between groups, alongside the increases in cumulative revenue and average order size, albeit inconsistently, it is recommended to conclude the test and declare Group B as the winner. This decision is supported by the substantial improvement in a key metric—average orders per visitor—which is crucial for business, coupled with no observed significant differences in average order size. Further analysis and anomaly correction may be necessary due to the variability in cumulative revenue and average order size trends observed in Group B.

This project's insights are pivotal for decision-making in enhancing revenue strategies for the internet store.
