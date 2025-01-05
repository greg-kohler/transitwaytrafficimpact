# Traffic Prediction

The contents of this contain the code and data needed to train a model to predict traffic changes after the construction of planned transitways in the Twin Cities metro area. This utilizes 4 datasets and trains a XGBRegressor. For results, the code compares traffic change for roadways with and without planned transitways to detect any noticeable impact. 

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

Final Project - Traffic - 1st Draft.ipynb - Notebook that contains all code needed for workflow
Required Data Folder - Contains all data needed to run the Notebook
Results Folder - Contains final result shapefile, visualization, and analysis results. 
README.md - File to introduce the project and instructions on the code

## Data

Data was obtained from the Minnesota Geospatial Commons.
Transitway Alignments Generalized: https://gisdata.mn.gov/it/dataset/us-mn-state-metc-trans-transitways-generalized
Bus Routes: https://gisdata.mn.gov/it/dataset/us-mn-state-metc-trans-transit-routes (Manually modified to include opening years sourced from Wikipedia.org)
Traffic Segments: https://gisdata.mn.gov/en/dataset/trans-aadt-traffic-segments
Historical Traffic Data: https://gisdata.mn.gov/en/dataset/trans-historic-aadt

## Usage

To use the code, simply copy the data from the required data folder into the same folder as the notebook. Then, run each cell of the notebook in order. The notebook will create several shapefiles as a form of quality control. The end result will display average percent changes in traffic for comparison, as well as a visualization. The notebook will also output a shapefle with the predicted traffic changes. The output used for comparison can be seen in the code block labeled "Calculate results for analysis." 

## Limitations

This code was created as a proof of concept. It makes several assumptions about traffic trends and is not meant to be used beyond practice with model training. 

## Credits

This code was created by Greg Kohler with assistance from ChatGPT. 
Data obtained from Minnesota Geospatial Commons
