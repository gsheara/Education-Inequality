# Education-Inequality
This repository is for the education inequality project. It will compare socioeconomic and demographic information based on census tract data for different schools, and examine them as possible predictors of high school students' SAT or ACT scores.

# Description
The exported data sets were used in a basic train-test model to analyze if socioeconomic factors can be used as predictors of high school average ACT scores, and if so to what extent. Ultimately, numerical demographic and income data can be used to predict ACT score within about a point and a half, with a dropoff in prediction accuracy for higher average scores. Unemployment rate may be the strongest predictor of average ACT score.

A Google Slides presentation containing a summary of the steps in this project may be found here: https://github.com/gsheara/Education-Inequality/blob/656eb6df85471d92fa0368e09bcb65d1fa97ff23/Communicate%20the%20Results.pdf 

# Requirements
This project utilizes the CSV files included in this GitHub repository, Google Colab as a Python IDE, and a few common Python libraries for math and data visualization (pandas, numpy, matplotlib, scikitlearn, and Altair-vega).

# Data
The data utilized for this project comes from EdGap.org, an online tool for visualizing factors contributing to standardized testing results across the United States, and the National Center for Education Statistics (school info dataset).

Education Gap dataset link: https://github.com/gsheara/Education-Inequality/blob/373577c9a9887a1c77aeed25b1a6cdb50109bc72/EdGap_data.xlsx

School Info dataset link: https://drive.google.com/file/d/1HvW2w-o2XZzCm4KTvnb1Bb3BvoAa14BP/view 

# Data preparation
The data for this project was prepared by filtering out extraneous columns, setting impossible values to null, and then imputing null values using the InteractiveImputer tool as fitted to a randomly sampled training set of the data. 

The notebook for data preparation can be found here: https://github.com/gsheara/Education-Inequality/blob/544855bf5d894b3e4ab6264a956501df9b2274de/Data_Preparation.ipynb

The notebook for data analysis can be found here: https://github.com/gsheara/Education-Inequality/blob/730675bed0cbf6ba3a91031ac5e97a268e997b95/Education_Analysis.ipynb

This data prep phase produced four clean datasets, a train and test for the numerical and categorical data. The categorical data is used to answer the question proposed in the additional step and focuses solely on school type. The CSVs for these datasets can be found here:

Numerical training dataset: https://github.com/gsheara/Education-Inequality/blob/544855bf5d894b3e4ab6264a956501df9b2274de/NumTrain.csv

Numerical test dataset: https://github.com/gsheara/Education-Inequality/blob/544855bf5d894b3e4ab6264a956501df9b2274de/NumTest.csv

Categorical training dataset: https://github.com/gsheara/Education-Inequality/blob/544855bf5d894b3e4ab6264a956501df9b2274de/CatTrain.csv

Categorical test dataset: https://github.com/gsheara/Education-Inequality/blob/544855bf5d894b3e4ab6264a956501df9b2274de/CatTest.csv

# Authors
This project and corresponding repository was created by Genny Sheara for an assignment in DATA 3320: Data Methodologies at Seattle University. LinkedIn: https://www.linkedin.com/in/genny-sheara/

# License
All data and tools utilized for this project are open source and reproducible by anyone.
