# Real Estate Listings Analysis

## Project Description
This project involves analyzing historical data from the Real Estate service, which includes listings of apartments for sale in Saint Petersburg and nearby localities over several years. The objective is to determine the market value of real estate properties and identify typical apartment parameters.

## Data Description
The dataset contains the following information:

- **airports_nearest**: Distance to the nearest airport (meters)
- **balcony**: Number of balconies
- **ceiling_height**: Ceiling height (meters)
- **cityCenters_nearest**: Distance to the city center (meters)
- **days_exposition**: Number of days the listing was published
- **first_day_exposition**: Publication date
- **floor**: Floor number
- **floors_total**: Total number of floors in the building
- **is_apartment**: Whether the property is an apartment (boolean)
- **kitchen_area**: Kitchen area (square meters)
- **last_price**: Price at the time of delisting
- **living_area**: Living area (square meters)
- **locality_name**: Name of the locality
- **open_plan**: Open plan (boolean)
- **parks_around3000**: Number of parks within 3 km
- **parks_nearest**: Distance to the nearest park (meters)
- **ponds_around3000**: Number of water bodies within 3 km
- **ponds_nearest**: Distance to the nearest water body (meters)
- **rooms**: Number of rooms
- **studio**: Whether the property is a studio (boolean)
- **total_area**: Total area of the apartment (square meters)
- **total_images**: Number of images in the listing

## Libraries Used
- Pandas
- NumPy
- Matplotlib

### Key Findings:
- **Apartment Characteristics**:
  - Typical apartments have an average total area of about 50 sq.m and are priced around 5 million rubles.
  - Most listings feature 1-3 room apartments and are located on the first floors of five and ten-story buildings.
- **Location Impact**:
  - Proximity to the city center and airports significantly affects property prices.
  - Most apartments are within 20 km of the city center.
- **Listing Activity**:
  - Listings are more active on weekdays, with peak periods in February-April and September-November.
  - The average selling time for apartments is 95 days.
- **Price Correlation**:
  - Apartment prices are closely linked to parameters like total area, floor number, and publication time.
These insights are valuable for developing successful real estate sales and purchase strategies in the region.
