Introduction:
---

In this project, we will build a machine learning model which will accurately predict the travel time of a taxi trip in New York City. After constructing features from the dataset, we try to build different machine learning models, including linear regression model (OLS, Lasso, Ridge), random forest and adaboost model. The importance of features is evaluated based on different kind of models. We compare the performance of each model and choose the best one as our final model.  

Files:
---

**Final_Project.ipynb** - The main notebook for the project.\
**Col_Extraction.ipynb** - The notebook to extract num_accident for train and test dataset.\
**prediction.csv** - The prediction result based on the best model.\
**data fold** - including datasets used in the project

Dataset:
---
The datasets are extracted from the bigquery.

**New York Taxi Data** - bigquery-public-data.new_york.tlc_yellow_trips_2016\
**New York Weather Data** - bigquery-public-data.noaa_gsod.gsod2016\
**New York Accident Data** - bigquery-public-data.new_york_mv_collisions.nypd_mv_collisions

