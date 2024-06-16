# Analysis of a Food Sales Startup

## Project Description
The goal of this project is to analyze user behavior in a mobile application for a food sales startup. The analysis focuses on two main objectives:

1. **Sales Funnel Analysis**: Understand how users progress through the sales funnel. Identify how many users complete purchases and where users drop off.
2. **A/A/B Experiment Analysis**: Evaluate the impact of a font change in the app. Determine if the new font affects user behavior by analyzing the results of the A/A/B test.

## Data Description
The dataset includes events from the mobile application, with the following fields:

- **EventName** — Name of the event
- **DeviceIDHash** — Unique identifier for the user
- **EventTimestamp** — Time of the event
- **ExpId** — Experiment ID: 246 and 247 are control groups with the old fonts, and 248 is the experimental group with the new font.

## Libraries Used
- pandas
- numpy
- datetime
- matplotlib
- seaborn
- scipy
- statsmodels

## Conclusions
 - The proportion of users who progressed from the main screen to successful payment is 0.47, meaning approximately 47% of users complete the purchase after passing through all stages of the funnel.
 - The results of the A/A/B test showed that the font change does not affect user behavior, as no statistically significant difference was observed between the groups studied.
