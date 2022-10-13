# Generic Real Estate Consulting Project
Groups should generate their own suitable `README.md`.

# MAST30034 Project 1 README.md
Group 50:
- Name: Yuan Li
- Student ID: 1067996

- Name: Keru Wu
- Student ID: 1066278

- Name: Yinyin Zhang
- Student ID: 1078236

- Name: Xiaoxuan Yan
- Student ID: 1068135

- Name: Yan Zhuang
- Student ID: 1178869

**Research Goal:** My research goal is to determine the appropriate level of rent of an online real estate company, find the most important internal and external features in predicting rental prices, find the top 10 suburbs with the highest predicted growth rate and find the most liveable and affordable suburbs.

**Timeline:** The timeline for the research area is 2018 - 2025.

To run the pipeline, please visit the `notebooks` and `models` directory and run the files in order:
1. `domain_scrape.ipynb`: This notebook scrapes all the internal features on rental property websites in Victoria in 2022.
2. `convert_json_to_csv.ipynb`: This notebook preprocesses the internal property data and converts the data from JSON format to CSV format.   
3. `mean_weekly_price.ipynb`: This notebook calculates the mean weekly rental price in each postcode.
4. `VictoriaGeolocation.ipynb`: This notebook plots the geomap of Victoria according to postcodes.
5. `postcode_centroid.ipynb`: This notebook extracts the postcodes in Victoria and corresponds to the centroid longitude and latitude on the postcode.
6. `distance_station.ipynb`: This notebook calculates the distance and duration from each bus station to the nearest centroid and only remains the hospital that is closest to the centroid.
7. `bus_station_geomap.ipynb`: This notebook plots all the bus stations on the geomap.
8. `distance_hospital.ipynb`: This notebook calculates the distance and duration from each hospital to the nearest centroid and only remains the hospital that is closest to the centroid.
9. `distance_school.ipynb`: This notebook calculates the distance and duration from each school to the nearest centroid and only remains the hospital that is closest to the centroid.
10. `distance_shopping_center.ipynb`: This notebook computes the closest distance for all the shopping centers to the centroid and the duration from each shopping center to the centroid.
11. `population.ipynb`: This notebook only contains population data in victoria and aggregate population with respect to postcode.
12. `predicted_income.ipynb`: This notebook predicts the income for 2020 to 2025.
13. `income_visualization.ipynb`: This notebook plots the rent distribution on the map.
14. `income_visualization_1.ipynb`:This notebook plots the graph with predicted income as well as the current existing income only.
15. `count.ipynb`: This notebook counts the number of hospitals, schools, shopping centers and bus stations on each postcode.
16. `Merge.ipynb`: This notebook merges all the external features to the main property data.
17. `outlier_removed.ipynb`: This notebook removes outliers and fills missing data based on ‘complete_data’.
18. `question1_feature_selection.ipynb`: This notebook computes and selects the most important features in predicting rental prices.
19. `RF_model.ipynb`: This notebook builds a random forest regression model and makes the predictions for the future weekly rent.
20. `NN_model.ipynb`: This notebook includes all the codes related to our neural network model. 
21. `Visualization.ipynb`: This notebook plots the geomap of population distribution, crime count distribution, weekly rental price distribution, station number distribution, hospital number distribution and shopping center number distribution.
22. `rent_visualization.ipynb`: This notebook plots the rent distribution on geomap.
23. `radar.ipynb`: This notebook includes all the codes related to radar plot and growth rate geo map.