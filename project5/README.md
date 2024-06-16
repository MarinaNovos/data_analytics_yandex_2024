# Analysis of the Procrastinate Pro+ App Data

## Project Description
Despite significant investments in advertising, the Procrastinate Pro+ app has been experiencing losses in recent months. The objective is to analyze user data to understand the causes and help the company achieve profitability.

## Data Description
The dataset includes data on users acquired between May 1 and October 27, 2019, covering server logs of their visits, purchase records, and advertising expenses. The data is structured as follows:

### visits_info_short.csv
- **User Id** — Unique user identifier
- **Region** — User's country
- **Device** — User's device type
- **Channel** — Advertising source identifier
- **Session Start** — Session start date and time
- **Session End** — Session end date and time

### orders_info_short.csv
- **User Id** — Unique user identifier
- **Event Dt** — Purchase date and time
- **Revenue** — Order amount

### costs_info_short.csv
- **dt** — Date of the advertising campaign
- **Channel** — Advertising source identifier
- **costs** — Campaign costs

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- datetime

## Conclusions
Key insights derived from the analysis are as follows:

- **User Conversion**: The conversion rate from initial visit to purchase completion is 8%, indicating potential issues with user acquisition strategies or product attractiveness.
- **Regional Performance**: The USA has the highest number of users and paying customers but shows low advertising ROI. 
- **Device Performance**: Users with iPhones and Macs (Apple devices) have high acquisition costs and slower ROI, despite a steady increase in LTV.
- **Channel Performance**: Advertising channels such as 'TipTop' and 'FaceBoom' incur high costs but yield low ROI, suggesting a need for strategic revision.
- **Advertising Spend**: A sharp increase in acquisition costs in the USA in June significantly impacted ROI, indicating possible inefficiencies in that period.

## Recommendations
- **Budget Optimization**: Reallocate budget to channels with lower acquisition costs and higher paying customer percentages, such as 'AdNonSense' and 'RocketSuperAds'.
- **US Market Analysis**: Investigate the reasons for the sharp increase in acquisition costs in June and optimize strategies accordingly.
- **Device-Specific Strategies**: Enhance conversion rates and ROI for iPhone and Mac users through targeted, personalized advertising.
- **Channel Monitoring**: Regularly monitor advertising campaign performance and adjust strategies promptly to maximize ROI.

Implementing these recommendations can help improve the efficiency of marketing campaigns and enhance overall profitability.