# Traffic Prediction

This contains the code needed to train a model to predict traffic changes after the construction of planned transitways in the Twin Cities metro area. This utilizes 4 datasets and trains an XGBRegressor. For results, the code compares traffic changes for roadways with and without planned transitways to detect any noticeable impact. 

## Requirements

geopandas
numpy
pandas
sklearn.model_selection
sklearn.metrics
xgboost
warnings
matplotlib.pyplot as plt

## Contents

Final Project - Traffic.ipynb - Notebook that contains all code needed for workflow
Results Folder - Contains final result visualization, and analysis results. 
README.md - File to introduce the project and instructions on the code

## Data

Data was obtained from the Minnesota Geospatial Commons.
Transitway Alignments Generalized: https://gisdata.mn.gov/it/dataset/us-mn-state-metc-trans-transitways-generalized
Bus Routes: https://gisdata.mn.gov/it/dataset/us-mn-state-metc-trans-transit-routes (Manually modified to include opening years sourced from Wikipedia.org)
Traffic Segments: https://gisdata.mn.gov/en/dataset/trans-aadt-traffic-segments
Historical Traffic Data: https://gisdata.mn.gov/en/dataset/trans-historic-aadt

## Limitations

This code was created as a proof of concept. It makes several assumptions about traffic trends and is not meant to be used beyond practice with model training. 
