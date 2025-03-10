# Airbnb Seattle Tableau Dashboard

## Overview
This Tableau dashboard provides insights into Airbnb listing activity in Seattle, WA, using data sourced from Kaggle. The dataset consists of three tables:
- **Listings**: Includes full descriptions and average review scores.
- **Reviews**: Contains unique reviewer IDs and detailed comments.
- **Calendar**: Includes listing IDs, price, and daily availability.

## Data Processing
To create the dashboard, an **inner join** was performed using:
- `id` column from the **Listings** table.
- `listing_id` column from both **Reviews** and **Calendar** tables.

## Dashboard Components
The dashboard consists of six visualizations:

1. **Average Price per Bed Type** (Bar Graph)  
   - Displays average price per bed type for **2016 and 2017**.
   
2. **Average Price per Bedrooms** (Bar Graph)  
   - Shows price variations based on the number of bedrooms.
   
3. **Distinct Count of Bedroom Listings** (Bar Graph)  
   - Represents the number of listings categorized by bedroom count.
   
4. **Price per Zipcode** (Map)  
   - Visualizes Airbnb prices across different Seattle zip codes.
   
5. **Average Review per City** (Bar Graph)  
   - Compares average reviews for different cities across **2016 and 2017**.
   
6. **Revenue for 2016** (Line Graph)  
   - Tracks revenue trends over the weeks of **2016**.
![Airbnb Seattle Dashboard]([https://your-image-url.com/dashboard.png](https://github.com/20hnu/Tableau_dasdboard/blob/main/Dashboard%201.png))

## Usage
This dashboard provides a comprehensive analysis of pricing, availability, and user engagement trends in the Seattle Airbnb market. It can be useful for hosts, travelers, and analysts looking to understand market behavior over time.
The image of dashboard is provided in png format.
**Dataset Source**: [Kaggle - Airbnb Seattle](https://www.kaggle.com/datasets/airbnb/seattle)  

