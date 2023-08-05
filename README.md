# King County Housing Prices: Phase2_Project


#### Project by: Lucas Wilkerson
#### Date: 8/7/2023

## Project Overview

Using housing price data from King County, I sought to explore what housing characteristics have the biggest infleunce on the price of a home in King County. Using linear regression, the aim is to take these housing characteristics and build a model to accurately predict housing prices based on these housing features. 

## Business Problem/Stakeholder

A real estate company in King County wants to increase customer acquisition and retention by providing transparent and useful information regarding the sales prices of homes. Utilizing this data, they can assist customers/clients that are looking to sell their home, understand what to expect to sell their current home for and what areas they could look into to increase the value of their home before selling. Utilziing our analysis and model, the goal is to help homeowners make informed decisions by assessing how factors like home condition, size (square footage) and other can impact their home's estimated value. Using this, homeowners can focus on the most important features to address in order to maximize their sale price. 


## Data Undertsanding 

For our analysis, we utilized the King County House Sales dataset. 
- kc_house_data.csv

Upon initial analysis, this dataset has 30,155 entries with a total of 25 columns (containing both numeric and object data) which represent the various features and characteristics of the homes along with the sale price. After data cleaning and preparation, which involved dropping missing values and duplicates, dropping unnecessary columns, and transforming certain columns, our clean working dataset now consists of 30,062 entries with 21 columns:

- Each row contains data of an individual house 
- The data in the columns represent the features/characteristics of the home. 
- After data preparation, all columns were adjusted to be numeric variables.

Final columns/features used include: 

- price: Sale price                 
- bedrooms: Number of Bedrooms            
- bathrooms: Number of Bathrooms           
- sqft_living: Square footage of living space           
- sqft_lot: Square footage of the lot              
- floors: Number of floors (levels) in house               
- grade: Overall grade of the house. Related to the construction and design of the house.                  
- sqft_above: Square footage of house apart from basement             
- Basement: Whether the house has a basement area      
- Garage: Whether the house has a garage area                 
- Patio: Whether the house has a patio area                  
- yr_built: Year when house was built               
- Waterfront: Whether the house is on a waterfront            
- Greenbelt: Whether the house is adjacent to a green belt              
- Nuisance: Whether the house has traffic noise or other recorded nuisances               
- view_encoded: Quality of view from house          
- condition_encoded: How good the overall condition of the house is. Related to maintenance of house.       
- heat_source_encoded: Heat source for the house    
- sewer_system_encoded: Sewer system for the house  
- month: Month the house was sold                   
- Age: Age (years) of the house when sold                  
- renovated: Whether the house has been renovated             


## Modeling 

Distribution of Sale Prices
![Price_histogram](Images/Price_histogram.png)





## Regression Results 

## Conclusion/ Recommendations 