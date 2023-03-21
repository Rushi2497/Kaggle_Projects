# House_Price_Prediction

A regression problem and my second project on Kaggle about predicting the house prices in Ames, Iowa.<br>
The link to the datasets available on Kaggle - https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

### Files and description:
1\. train.csv<br>
Training dataset provided on Kaggle. Contains target values for house prices.<br><br>
2\. test.csv<br>
Testing dataset provided on Kaggle for submitting predictions. Does not contain target variable.<br><br>
3\. submission.csv<br>
Submission file for Kaggle containing price predictions for respective house ID.<br><br>
4\. data_description.txt<br>
A file containing description of all the 81 columns present in the dataset.<br><br>
5\. House_Price_Regression_using_Ensemble_Models.ipynb<br>
A fully documented notebook with markdowns explaining the entire process right from data cleaning to making predictions.

### Learnings:
1. Data Cleaning
>Performed imputations on missing data based on the data type - median imputing for numerical features, mode and 'NA' imputing for categorical features. Dropped columns that were redundant or had a sizeable amount of data missing.
2. Feature Engineering and Data Preprocessing
> Converted ordinal categories to numerical features, log-normalized numerical data and smartly dealt with rare categorical data to reduce the cardinality of features.
3. Exploratory Data Analysis
> Univariate and bivariate analysis of features present in the dataset. Decisions for feature engineering and data preprocessing were taken based on the EDA.
4. Cross validation, hyperparameter tuning and ensembling
> Selected ML models to use basis cross validation score. Tuned hyperparameters using GridSearchCV and RandomSearchCV for the selected ML models. Based on the scores on the validation set, four models were selected - ElasticNet, SVR, GradientBoost and XGBoost. These 4 models were ensembled using Scikit-Learn VotingRegressor.
5. Implementing pipelines
> Used Scikit-Learn's Pipeline and ColumnTransformer module to create a pipeline consisting of all data preprocessing, feature engineering, ensembling and training steps. Created custom transformers for these steps leveraging OOPS knowledge.

I am open to suggestions and will be happy to know how I can make my notebooks look better or how I can increase the accuracy of my ML pipeline.
