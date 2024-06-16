# Data Analysis of Scooter Rental Service 

## Project Description
This project involves analyzing user and trip data from the popular scooter rental service across several cities. The goal is to analyze the data and test hypotheses that can help the business grow. Users access the service via a mobile app, with two usage options: without a subscription and with an Ultra subscription.

## Data Description
The datasets provided are:
- **users_go**: Information about users.
  - **user_id**: Unique user identifier.
  - **name**: User's name.
  - **age**: User's age.
  - **city**: City of the user.
  - **subscription_type**: Subscription type (free, ultra).

- **rides_go**: Information about trips.
  - **user_id**: Unique user identifier.
  - **distance**: Distance traveled in the current session (meters).
  - **duration**: Session duration (minutes).
  - **date**: Date of the trip.

- **subscriptions_go**: Subscription details.
  - **subscription_type**: Type of subscription.
  - **minute_price**: Cost per minute for the subscription.
  - **start_ride_price**: Start fee for the subscription.
  - **subscription_fee**: Monthly subscription fee.

## Libraries Used
- Pandas
- Matplotlib
- NumPy
- SciPy (binom, norm)
- Math (sqrt)

## Analysis Summary
The analysis involved a comprehensive data processing cycle for the GoFast scooter rental service. Tasks included data loading, preprocessing, and exploratory data analysis. The user, trip, and subscription data were merged, and revenue was calculated. Hypotheses about user behavior with and without subscriptions were tested, and promotional distribution analysis was conducted.

### Key Findings:
1. **User Engagement**:
   - Users with subscriptions are more active, spending more time on trips. This indicates potential for more effective marketing and subscriber retention strategies.
2. **Trip Distance**:
   - The average distance per trip for Ultra subscription users does not exceed 3130 meters, which aligns with optimal parameters, confirming the attractiveness of the Ultra subscription.
3. **Revenue Analysis**:
   - A significant increase in monthly revenue from subscribers highlights their importance to the company's financial success.
4. **Promotion Strategy**:
   - For a successful subscription renewal campaign, it is recommended to send approximately 850 promo codes to ensure a more than 5% renewal success rate.
   - When sending 1 million push notifications, it is expected that fewer than 399.5 thousand users will open the notification. Revisiting the notification strategy to increase its effectiveness is recommended.

### Recommendations:
- **Enhance Marketing Efforts**: Focus on marketing strategies that emphasize the benefits of the Ultra subscription to increase user engagement and subscription rates.
- **Optimize Subscription Offers**: Ensure the Ultra subscription remains attractive by maintaining or improving its cost-benefit ratio.
- **Refine Promotion Strategies**: Implement targeted promotional campaigns and improve push notification strategies to increase engagement and effectiveness.
These insights provide valuable guidance for strategic decisions aimed at enhancing user experience and boosting the financial performance of the GoFast scooter rental service.
