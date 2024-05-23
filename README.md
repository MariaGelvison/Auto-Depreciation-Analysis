# Consumer Guide to Car Buying-- UAE Auto Sales Data as proxy to Global Car Sales

## Table of Contents

  - [Project Overview](#project-overview)
  - [Data Analysis](#data-analysis)
  - [Insights](#insights)
  - [Recommendations](#recommendations)
    

## Project Overview
This analysis aims to analyze the value of cars as it age, the depreciation. This aims to guide consumer for buying a car. I will be using the same dataset, the UAE Auto Sales Data as proxy to Global Car Sales. 

### Data Sources
The primary dataset used for this analysis is the "car_dataset_uae.csv" file, cleaned data. 
You can also download the main dataset from kaggle [Download here](https://www.kaggle.com/datasets/azharsaleem/uae-auto-market-sales-data-for-advanced-analytics)


### Data Structure Overview
Column Headers: brand, model, car_name, car_category, price, trim, kilometers, year, vehicle_age_years, regional_specs, doors, body_type, fuel_type, seating_capacity, transmission_type, engine_capacity_cc, horsepower, no_of_cylinders, exterior_color, interior_color, warranty, address, country, city, area_name, location_name, seller_type, lat, long.


### Data Cleaning

Data Cleaning was mainly done using Excel which performed the ff tasks:
1. Data loading and inspection
2. Handling missing values
3. Treating outliers
4. Data Cleaning and formatting

### Data Preparation and Data Validation

1. Carefully created a column “Categories” and manually classified each car into the following factors:
    - market positioning
    - body type
    - dimension
    - features, and
    - appointments

  Different car models are made to cater to a wide variety of consumer wants and needs.


2. Car prices adjustment
   - Erronous data prices were observed, seems like three zeros "000" were missing for some 'high-end' car prices (might be a typo error). And thus, changing them into a more realistic amount by multiplying them into "1000" could create a more realistic analysis. Google seach helped to validate the data.

## Data Analysis

### Depreciation

1. Study the relationship between the car age and average price to understand the depreciation trends.
2. Compare how different categories depreciates over time.


![image](https://github.com/MariaGelvison/AutoMarketSales_UAE_Part2/assets/170020192/b3f77039-10a3-4b79-a463-b17a24ba9928)

![image](https://github.com/MariaGelvison/AutoMarketSales_UAE_Part2/assets/170020192/aec76e3d-7e72-4cd5-b40f-bc780c3be531)

![image](https://github.com/MariaGelvison/AutoMarketSales_UAE_Part2/assets/170020192/7d29709e-40dd-494d-b1fa-b3047dc0fa8d)

![image](https://github.com/MariaGelvison/AutoMarketSales_UAE_Part2/assets/170020192/b1d07eb0-651b-4c19-a459-7b77dd86e5ca)

![image](https://github.com/MariaGelvison/AutoMarketSales_UAE_Part2/assets/170020192/a6368c4f-d216-4ae9-8067-7b27a8a9df9c)

![image](https://github.com/MariaGelvison/AutoMarketSales_UAE_Part2/assets/170020192/4343d04a-5a38-423b-9454-7320a3f80c8b)

![image](https://github.com/MariaGelvison/AutoMarketSales_UAE_Part2/assets/170020192/8e7b8f47-a9d0-4ceb-94b0-e9328b3f9e58)


### Insights

  -  Expensive vehicles lose on average 20% of their value year on year;
  -  Base cars only lose on average 10% of their value year on year;
  -  Not true for sports cars.

### Recommendation

  - Those considering buying a brand new vehicle may consider looking the affordable base models as they tend to hold value better
  - If preference is a premium model, certified pre-owned vehicles are a good option as depreciation slows down after 5 years.

















