This repository is about an EDA (explorative data analysis on a Seattle Airbnb dataset from 2016)
The EDA takes the perspective of a fictious room provider who wants to find a fair price for his room, 
by looking at the prices others have offered for similar rooms.

It answers the questions:
1. What is the price profile of different locations?
2. How does the season relate to the price?
3. How do room type, property type and amenities relate to the price?
It also predicts the price with an XGBoost regression model

A high level article about the results can be found here:
https://medium.com/@ziesl/how-to-choose-an-intial-price-for-airbnb-hosting-c662b76a0090



Repository content
############################
- eda_Airbnb_Seattle.ipynb: A jupyter notebook, containing the EDA 
- environment_Seattle.yml: A yml to create a conda environment for the notebook (To run it: "conda env create -f environment_Seattle.yml")
- eda_Airbnb_Seattle.html: The html export of the notebook
- Data folder: Contains the datasets, exported from: https://www.kaggle.com/datasets/airbnb/seattle/data


Libraries used
############################
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn
- xgboost



Acknowledgements
############################
Dataset:
Seattle Airbnb Open Data (link: https://www.kaggle.com/datasets/airbnb/seattle/data)
The dataset is part of Airbnb Inside, and the original source can be found here: https://insideairbnb.com/get-the-data/

