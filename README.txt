This repository is about an EDA (explorative data analysis on a Seattle Airbnb dataset from 2016)
The EDA takes the perspective of a fictious room provider who wants to find a fair price for his room, 
by looking at the prices others have offered for similar rooms.

It answers the questions:
1. What is the price profile of different locations?
2. How does the season relate to the price?
3. How do room type, property type and amenities relate to the price?

It also tries to predict the price with an XGBoost regression model



The repository contains:
- eda_Airbnb_Seattle.ipynb: A jupyter notebook, containing the EDA 
- environment_Seattle.yml: A yml to create a conda environment for the notebook (To run it: "conda env create -f environment_Seattle.yml")
- eda_Airbnb_Seattle.html: The html export of the notebook
- Data folder: Contains the datasets, exported from: https://www.kaggle.com/datasets/airbnb/seattle/data