# Titanic Survivor Prediction with H2O AutoML
From Kaggle competition Titanic: Machine Learning from Disaster: https://www.kaggle.com/c/titanic

The original Kernel can be acessed here, to see ProfileReport made by Pandas Profiling: https://www.kaggle.com/alexandrefarb/fastanic-fastai-pandas-profiling-h2o-automl?scriptVersionId=24255044

In this approach is made an approach using three Python modules as the pillars: fastai, Pandas Profiling and H2O, but why to use these modules? Because they can do so much work writing just a few lines of code speeding up the process, therefore the name "Fastanic".

The fastai loads a lot of useful modules, as Pandas and Numpy, Pandas Profiling can generate a detailed Exploratory Data Analysis (EDA) with just one code line and H2O using its AutoML module can train different Machine Learning models and ensemble it to make good predictions, but remember there's No Free Lunch, fastai is good but maybe you will need other modules to make your EDA, Pandas Profiling is not good to report in large datasets (I tried to use on Porto Seguro Safe Driver Prediction Dataset without sucess) and H2O AutoML can take a big amount of time to train all the models.

The Legendary Competition to predict the survivors of Titanic Disaster is a good start point to apply these great modules and understand how to work with them and know their pros and cons. This dataset is small enough to use these tools and give a good idea when to use they and we can dedicate more time to understand the data and apply Feature Engineering (FE) to it.
