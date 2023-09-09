Our project consist of 2 different approaches to build ML models for our dataset and predict the price of a used car based on certain parameters. We also performed basic Data analysis on Tableau creating different Charts for Data visualization

A) The first approach was working on Google collab using Python and its libraries.

The flow of our project consists of the following steps:

1. Importing important libraries
2. Data cleaning and preprocessing
3. EDA
4. Feature selection
5. Building models (Such as Lasso Regressor, Ridge Regressor, Random Forest Regressor, Catboost Regressor, XGBoost Regressor, Neural Network Regressor)
6. Overall comparision of all models used

The conclusion being, Neural Network Regressor works well on our data and can be used as the model that will give the final prediction when we deploy it.

B) In the second approach we performed ETL on an Apache VirtualBox using various Big data tools in the process.

1. Firstly the original dataset was uploaded to the HDFS
2. A table was created in Hive and the location of file in HDFS was provided.
3. Pyspark and Hive connectivity was established
4. Basic Data preprocessing was done and we used a Random Forest model from the Mllib library
5. Lastly transformations were performed onto the data and the newly transformed files loaded back to HDFS
