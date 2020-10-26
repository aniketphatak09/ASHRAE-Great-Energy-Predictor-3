# ASHRAE-Great-Energy-Predictor-3

ASHRAR- Great Energy Predictor mainly deals with finding accurate models of metered buildings energy. There are various areas provided such as chilled water,electric, hot water and steam water. The data is derived from more than 1000 buildings within a three-year timeframe. The major motive behind this project is to predict continues values of energy consumption hence a Regression Problem where we develop a model custom tailored for different use case scenarios such the consumers could benefit from reduced costs compared to the conventional retro fitted model. Since conventional models do not scale well since a specific meter type doesn’t work with different building type.

- The Fully connected MLP is our best performing model.

- Dataset available at:
https://www.kaggle.com/c/ashrae-energy-prediction


- Use the files under data folder to obtain train and test .csv files which are used as a testbench for training and testing of 3 models.
These files include:
 building_metadata,
 sample_submission,
 test,
 train,
 weather_test,
 weather_train

- Baseline code and analysis links:

 https://www.kaggle.com/jaseziv83/a-deep-dive-eda-into-all-variables
 
 https://www.kaggle.com/isaienkov/keras-nn-with-embeddings-for-cat-features-1-15
