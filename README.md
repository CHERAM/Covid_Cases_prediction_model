# FLIPR HACKATHON 5.0
This repo contains the Jupyter notebook and associated data for the machine learning model for Covid_Cases prediction built based on the problem statement given.

# Description:
To build a machine learning model which will predict the Covid-19 Cases on the given cities in India.In this notebook, for working through the problem; pandas, numpy, Matplotlib will be used for data analysis and Scikit-learn, keras are used for machine learning and modelling tasks.

# Process:
The dataset is preprocessed and the  model is chosen after analysing the dataset. RandomForestRegressor is chosen here. The base model is trained using the train dataset from the preprocessed data and evaluated. Then, hyperparameter tuning is done by RandomizedSearchCV. The model is instantiated with the ideal parameters. The ideal model is trained with the train dataset. Validation dataset is used to evaluate the model. The model yielded good results. The prediction is done on the test data set and exported as excel file
