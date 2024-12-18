
# DS Project
<img width="845" alt="Screenshot 2024-12-18 at 9 42 13 AM" src="https://github.com/user-attachments/assets/9adca4f4-845a-4d67-94f0-a818e809e47c" />



## Authors

- [@akheirollahi](https://www.github.com/akheirollahi)

## Table of Contents

  - [Data source](#data-source)
  - [Business Problem Inspiration](#business-problem-inspiration)
  - [Methods](#methods)
 

## Data source

This dataset was created by web scraping over 200,000 car offers from one of the largest car advertisement sites in Poland.(https://www.otomoto.pl)
The dataset contains 208,304 observations of 25 variables.
Variables description:

ID - Unique ID of offer    
Price - the value of the price     
Currency - currency of the price (mostly Polish złoty, but also some euro)     
Condition - new or used     
Vehicle_brand - brand of vehicle in offer     
Vehicle_model - model of vehicle in offer     
Vehicle_generation - generation of vehicles in offer     
Vehicle_version - version of the vehicle in offer     
Production_year - the year of car production     
Mileage_km - the total distance that the car has driven in kilometres     
Power_HP - car engine power in horsepower      
Displacement_cm3 - car engine size in cubic centimetres     
Fuel_type - car fuel type      
CO2_emissions - car CO2 emissions in g/km     
Drive - the type of car drive     
Transmission - type of car transmission      
Type - car body style      
Doors_number - number of car doors       
Colour - car body colour       
Origin_country - country of origin of the car       
First_owner - whether the owner is the first owner       
First_registration_date - date of first registration       
Offer_publication_date - date of publication of the offer      
Offer_location - address provided by the issuer       
Features - listed car features (ABS, airbag, parking sensors etc.)      

- [Kaggle credit card approval prediction](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Business Problem Inspiration

- Display personalized advertisements tailored to the needs of the users. Cluster vehicles into distinct groups and find their specifications and meaningful patterns.

- Detect potentially fraudulent ads or rare vehicle listings. This analysis can help flag unusual pricing, suspicious descriptions, or rare features that might indicate a fraudulent listing of unique vehicles.
  
- Forecast the number of advertisements for the upcoming month that could influence website traffic and improve Ad platforms.
  
## Methods

- Clustering Algorithm(K-means)
- Anomaly Detection (Isolation Forest | DBSCAN )
- Time-Series Analysis (Decomposition)

Please refer to the report file to highlight the approach, results, and conclusions.

