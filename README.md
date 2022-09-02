# Data-Analysis-on-Kaggle-Dataset

Data Analysis or sometimes referred to as exploratory data analysis (EDA) is one of the core components of data science. It is also the part on which data scientists, data engineers and data analysts spend their majority of the time which makes it extremely important in the field of data science. This repository demonstartes some common exploratory data analysis methods and techniques using python. For purpose of illustration the used car database dataset has been taken from kaggle since it is one of the ideal dataset for performing EDA and taking a step towards the most amazing and interesting field of data science. Good luck with your EDA on the used car database dataset.

DataSet Overview
The dataset is taken from kaggle and contains details of the used cars in germany which are on sale on ebay.
The dataset is not clean and hence a lot of data cleaning is carried out. For e.g. prices where too high which are replaced by the median and outliers are removed accordingly.
Also vehicles whose registration year was greater than 2016 and less than 1890 were removed from the dataset as this data is inconsistense and would yield incorrect results.
The dataset is cleaned and stored in a CleanData folder which contains the entire cleaned dataset named as cleaned_autos.csv and another folder named DataForAnalysis containing files structures containing subsets of the cleaned dataset based on brand of the vehicles and vehicle types.
