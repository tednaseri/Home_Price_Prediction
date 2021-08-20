# Home Price Prediction

<ul align="justify">
<li>It is a supervised machine learning project based on the Kaggle Melbourne Homes Dataset which is made of 34857 records and 21 features. Each row represents one home.</li>
<li>It is a regression project where the goal is predicting home price.</li>
<li>The real dataset of the project has a noticeable amount of missing data. In fact, 14 features out of 21 features have missing values where different approaches were applied to impute them.</li>
<li>I have written different functions for repetitive tasks such as data cleaning, data preparation, data analysis, and plotting. Then, I just call these functions from the utils file to do these tasks.</li>
<li>For machine learning purposes, linear regression, random forest, XGBoost, and LightGBM are implemented. Model evaluation is done based on RMSE metric.</li>
<li>By optimizing the LGB model as the best model, we could decrease the RMSE metric by 4.81%.</li>
</ul>
  
# Files in this Repository:
<ol align="justify">
<li>Utils_Car_Insurance: This file includes common functions for tasks like data manipulation or data visualization. These functions will be called through other files.</li>
<li>Preparation_Car_Insurance: This file includes all the preparation steps for this dataset.</li>
<li>EDA_Car_Insurance: This file includes applied steps for the Data Explanatory Analysis.</li>
<li>Modeling_Car_Insurance: This file includes machine learning content of the project.</li>
</ol>

# How to run the project?
To run this project after downloading the dataset, the provided files should be run with the above order.

# Dataset:
The dataset for this project can be download from this link: https://www.kaggle.com/anthonypino/melbourne-housing-market

# More Details:
<p>More details are provided on my website at https://www.tednaseri.com/home_prices</p>
