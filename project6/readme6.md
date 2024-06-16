# Data Analysis of Video Game Sales for the Online Store "Streamlet"

## Project Description
This project involves analyzing historical sales data for video games available from open sources, including user and critic ratings, genres, and platforms (e.g., Xbox or PlayStation). 
The goal is to identify patterns that determine the success of a game, allowing us to focus on potentially popular products and plan advertising campaigns effectively. The data includes information up to 2016.

## Data Description
The datasets used contain the following information:
- **Name**: Name of the game
- **Platform**: Platform of the game
- **Year_of_Release**: Year the game was released
- **Genre**: Genre of the game
- **NA_sales**: Sales in North America (millions of copies sold)
- **EU_sales**: Sales in Europe (millions of copies sold)
- **JP_sales**: Sales in Japan (millions of copies sold)
- **Other_sales**: Sales in other countries (millions of copies sold)
- **Critic_Score**: Critic score (maximum of 100)
- **User_Score**: User score (maximum of 10)
- **Rating**: ESRB rating (Entertainment Software Rating Board) indicating the suitable age category for the game

## Libraries Used
- Pandas
- Matplotlib
- NumPy
- Seaborn

## Findings and Recommendations
The analysis of video game sales data involved data preparation and exploratory analysis. Column names were converted to lowercase, data types were corrected, and missing values were handled with explanations for the chosen methods and reasons for missing data.

### Key Findings:
1. **Release Trends**:
   - Most games were released after 2000, with peaks in 2008 and 2009.
   - Platforms with the highest total sales were identified, and sales distributions over the years for these platforms were plotted.
2. **Platform Sales**:
   - Leading platforms in terms of sales include PS2, X360, PS3, Wii, and DS.
   - The average lifespan of a gaming platform is approximately 9-10 years.
   - Regional preferences vary, with different platforms leading in sales in North America, Europe, and Japan.
3. **Genre Popularity**:
   - In North America and Europe, popular genres are Action, Sports, Shooter, Music, and Role-Playing.
   - In Japan, the popular genres are Role-Playing, Action, Music, Sports, and Platform.
4. **Impact of Reviews**:
   - The influence of reviews on sales is limited, with critic reviews having more weight than user reviews.
   - Scatter plots and correlation calculations were used to analyze the impact of user and critic reviews on sales.
5. **ESRB Rating Influence**:
   - The impact of ESRB ratings on sales in different regions was studied.
6. **Hypothesis Testing**:
   - Two hypotheses were tested:
     - No significant difference between average user ratings for Xbox One and PC platforms.
     - Significant difference between average user ratings for Action and Sports genres.

### Recommendations:
1. **Regional Customization**:
   - Consider regional preferences when developing content and marketing strategies.
2. **Critic Reviews**:
   - Utilize critic reviews judiciously to boost sales as they have a more significant impact than user reviews.
3. **Genre and Platform Focus**:
   - Focus on profitable genres (Action, Sports, Shooter, Music) and leading platforms (PS2, X360, PS3, Wii, DS) for better sales outcomes.
4. **Market Analysis**:
   - Regularly analyze market trends and adapt strategies to align with consumer preferences and platform lifecycles.
This analysis provides valuable insights for strategic decisions in the video game industry, aiding in the identification of potentially successful products and optimizing marketing efforts.
