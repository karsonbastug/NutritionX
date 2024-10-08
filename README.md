# NutriTrack Dashboard - Screenshot
<img width="952" alt="image" src="https://github.com/user-attachments/assets/ee3cf424-a32b-4316-a1d5-af7b630d8181">


## With Specific Food Selected

<img width="949" alt="image" src="https://github.com/user-attachments/assets/35401db6-c6e3-41cd-877a-79d583c1b48e">





# Purpose
The purpose of this project was to create a simplified way to keep track of your diet intake. By minimizing the input needed as a user, it encourages more frequent tracking of foods consumed, promoting your health.

# Functionality
The dhasboard utilizes NutritionX's food API to query the nutritional information. This API is called upon in Google Collab using Python code - users type in the food they consumed, and the API (nutrition information for that food) is called and stored in a published google sheet. This sheet is where the Power BI pulls its data from.

# Design
Originally, the Power BI was intended to utilize the REST API directly within the report to minimize the need of a third party. However, as of September 2024, Power BI does not currently support the historical storing of API results. As such, the data needs to be stored and the API called elsewhere. 

# Google Collab Code
Within this repository is the Python code being utilized in Google Collab. If you wish to use this code for your own report, you must retreieve your own API key and ID from NutritionX. Up to two keys/IDs can be obtained and used for free.

[Link to signup](https://www.nutritionix.com/business/api)

When you sign up, you will be prompted with the API key, ID, and documentaiton. Once you run the code, you will be ready to copy the Web link for the Google Sheet to Power BI to be utilized.

Have fun!




