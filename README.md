# Ironhack - Final Bootcamp Project - Spaceship Titanic

Spaceship Titanic is a competition sponsored by Google held on Kaggle. You can see more details about it clicking [here](https://www.kaggle.com/competitions/spaceship-titanic/overview)

The Spaceship Titanic is an interstellar passenger liner launched with almost 13000 passengers on board. When travelling to it's first destination the spaceship collided with a spacetime anomaly hidden in space and almost half of the passengers were transported to an alternate dimension. To help rescue the lost passengers we need to predict passengers were transported by the anomaly using data retrieved from the spaceship's computer system.

Clicking [here](https://public.tableau.com/views/FinalBootcampProject-SpaceshipTitanic/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link) you can see the Tableau Dashboard with some visualizations to help understand the trends in data.

-----------------

The final pipeline of the ML model consists in these steps:
 - SimpleImputer
 - Normalizer and OneHotEncoder
 - SelectKBest
 - GridSearchCV
 - XGBoost

-----------------

This repo contains 3 folders:
  - data:
    - raw data (train.csv and test.csv)
    - data after cleaning and feature extraction (train_transformed.csv and test_transformed.csv)
    - a formated file of the submissions to be uploaded on the competition (sample_submission.csv)
  - deliverables:
    - Jupyter notebooks used on this project
    - ML model saved via joblib
    - PowerPoint presentation
  - submissions:
    - the files uploaded to kaggle

------------------
