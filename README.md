# Road_Severity_Accident_Prediction_WebApp
Road Severity Accident Prediction Using Random Forest Classifier!

Check Out The Web App [Here]()


# Problem Statement

The task is to classify this variable based on the other 31 features step-by-step by going through each day's task. 
- The target feature is `Accident_severity` which is a multi-class variable.
- The metric for evaluation will be f1-score

# Dataset Used

Source of the dataset: [Click Here](https://www.narcis.nl/dataset/RecordID/oai%3Aeasy.dans.knaw.nl%3Aeasy-dataset%3A191591)

- The data set is collected from **Addis Ababa Sub-city police departments** for master's research work. 
- The data set has been prepared from manual records of road traffic accidents of the year **2017-20**. 
- All the sensitive information has been**excluded** during data encoding and finally it has <ins> 32 features</ins> and <ins>12316 instances</ins> of the accident.
- Then it is preprocessed for identification of major causes of the accident by analyzing it using different machine learning classification algorithms.

# Dataset Info
The following are metadata regarding the dataset:
- Time : Time of the accident (in 24 hours format) | 
-	Day_of_week : Day of the week when the accident occurred
-	Age_band_of_driver :The age group of the driver
-	Sex_of_driver : Gender of driver
-	Educational_level : Driver’s highest education level
-	Vehical_driver_relation : What’s the relation of a driver with the vehicle
-	Driving_experience : Number of years of driving experience the driver has
-	Type_of_vehicle : What’s the type of vehicle
-	Owner_of_vehicle : Who’s the owner of the vehicle
-	Service_year_of_vehicle : The last service year of the vehicle
-	Defect_of_vehicle : Is there any defect on the vehicle or not?
-	Area_accident_occured : Locality of an accident site
-	Lanes_or_Medians : Are there any lanes or medians at the accident site?
-	Road_allignment : Road alignment with the terrain of the land
-	Types_of_junction : Type of junction at the accident site
-	Road_surface_type : A surface type of road
-	Road_surface_conditions : What was the condition of the road surface?
-	Light_conditions : Lighting conditions at the site
-	Weather_conditions : Weather conditions
-	Type_of_collision : What is the type of collision
-	Number_of_vehicles_involved : Total number of vehicles involved in an accident
-	Number_of_casualties : Total number of casualties
-	Vehicle_movement : How the vehicle was moving before the accident occurred
-	Casualty_class : A person who got killed during an accident
-	Sex_of_casualty : What the gender of a person who got killed
-	Age_band_of_casualty : Age group of casualty
-	Casualty_severtiy : How severely the casualty was injured
-	Work_of_casualty : What was the work of the casualty
-	Fitness_of_casualty : Fitness level of casualty
-	Pedestrain_movement : Was there any pedestrian movement on the road?
-	Cause_of_accident : What was the cause of an accident?
-	Accident_severity : How severe an accident was? (Target variable)


# Steps Involved
All steps involved - Can be found in notebook too!

## EDA
- Importing the Dataset
- Check Metadata of the Dataset
- Find Number of Missing Values Present in Each Column
- Target Variable Classes Distribution & Visualization
- Check Education Levels of Drivers
- Auto Data Visualization Using the `Dabl` Library
- Check for Association Between `Road Surface Type` and `Accident Severity`

## Data Preprocessing & Feature Engineering
-  Converting the “Time” Column
-  Feature Selection General
-  Missing Value Treatment
-  One-Hot Encoding Using `get_dummies()`
-  Target Encoding using `LabelEncoder()`
-  Feature Selection Using **Chi2** Statistic
-  Imbalanced Dataset Treatment Using **SMOTENC** Technique

## Model Building, Evalaution & Saving
- Building a Random Forest Classification Model
- Evaluation: Classification Report & F1 Score
- Saving the Model & Encoder Object  using `joblib`

## Deploying
- Loading Model & Encoder 
- Preparing Streamlit Project Requirements 
  - requirements.txt 
  - github repo
- Creating `app.py` file which includes:
  - Initialising & Importing
  - User Input & Model Prediction
  - Webpage Aesthetics
- Deploying on Streamlit Community Cloud

DONE!

----

Reach out to me on: [Twitter](https://twitter.com/devloper_hs) |
       [Linkedin](https://www.linkedin.com/in/developerhs/) |
       [Blog(AV)](https://www.analyticsvidhya.com/blog/author/harsh1092/)
