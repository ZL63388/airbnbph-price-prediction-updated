## Airbnb PH Price Prediction
An updated personal version of the Capstone project based on the https://github.com/ZL63388/capstone-project-airbnb repository

## Reason for update
After the bootcamp, I continued my learning through Data Science Infinity program by Andrew Jones and understood more of the concept behind Regression models. I decided to use our Capstone project dataset to see if it improved the model and to apply what I have learned from the DSI program.

## Insights
1. Random Forest Regression from this updated model got better results and is not overfitting vs the Random Forest Regression used on our project
2. XGBoost dataset used from the Capstone project dropped several columns vs the updated Random Forest Regression model in this repository

   XG Boost dropped columns - url,rating,type_airbnb, province, is_shared_room, is_private_room, num_nearby_tourist_spots_3km,
                              num_nearby_supermarkets_3km, num_nearby_restaurants_3km,entire_home, latitude, longitude,
                              population,area,covid_total,covid_active, type_airbnb_label, province_label, foreign_travelers
   Random Forest dropped columns - url, population, area, foreign_travelers, covid_total, covid_active, longitude, latitude
