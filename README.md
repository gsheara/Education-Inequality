# Education-Inequality
This repository is for the education inequality project. It will compare socioeconomic and demographic information based on census tract data for different schools, and examine them as possible predictors of high school students' SAT or ACT scores.

# Data
The data utilized for this project comes from EdGap.org, an online tool for visualizing factors contributing to standardized testing results across the United States, and the National Center for Education Statistics (school info dataset).

Education Gap dataset link: https://github.com/gsheara/Education-Inequality/blob/373577c9a9887a1c77aeed25b1a6cdb50109bc72/EdGap_data.xlsx

School Info dataset link: https://drive.google.com/file/d/1HvW2w-o2XZzCm4KTvnb1Bb3BvoAa14BP/view 

# Data prep
The data for this project was prepared by filtering out extraneous columns, setting impossible values to null, and then imputing null values using the InteractiveImputer tool as fitted to a randomly sampled training set of the data. 

The notebook for data preparation can be found here: https://github.com/gsheara/Education-Inequality/blob/58381f492786bf6da7b7a8ddf8e428fc0d89e3b1/Data_Prep(FIXED).ipynb

The clean CSV it produced can be found here: https://github.com/gsheara/Education-Inequality/blob/main/Education-Inequality-clean-FIXED.csv
