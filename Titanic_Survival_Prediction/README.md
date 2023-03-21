# Titanic_Survival_Prediction
A classification problem and my first project on Kaggle about predicting which passengers survived on the RMS Titanic.<br>
The link to the datasets available on Kaggle - https://www.kaggle.com/competitions/titanic/data

### Files and description:
1\. train.csv<br>
Training dataset provided on Kaggle. Contains labels for survival (1-survived, 0-did not survive)<br><br>
2\. test.csv<br>
Testing dataset provided on Kaggle for submitting predictions. Does not contain labels.<br><br>
3\. submission.csv<br>
Submission file for Kaggle containing predictions for respective passenger ID.<br><br>
4\. Titanic_Survival_using_Logistic_Regression.ipynb<br>
A first cut notebook for predicting survival using Logistic regression. Notebook contains markdowns explaining the entire process right from preprocessing data to making predictions.<br><br>
5\. Titanic_Survival_using_advance_ML_Models.ipynb<br>
The final and more advanced version of finding predictions using models like Support Vector Machines and Random Forest. Also has a implementation of Scikit-Learn Pipeline and ColumnTransformer to aid in the quick preprocessing of test data. Notebook contains markdowns explaining the entire process and the code is fully documented.

### Learnings:
1. Data Cleaning
> Performed clever imputations like filling missing age values based on name titles. Dropped columns that were redundant or were missing too much data.
2. Feature Engineering and Feature Extraction
> Engineered new features like family size and extracted new information from ticket types of passengers to create another feature.
3. Exploratory Data Analysis
> Detailed univariate and bivariate analysis of features present in the dataset.
4. Cross validation and hyperparameter tuning
> Selected ML models to use basis cross validation score. Tuned hyperparameters using GridSearchCV.
5. Implementing pipelines
> Used Scikit-Learn's Pipeline and ColumnTransformer module to create a pipeline consisting of all preprocessing, feature engineering and training steps. Created custom transformers leveraging OOPS knowledge to add the pipeline.

I am open to suggestions and will be happy to know how I can make my notebooks look better or how I can increase the accuracy of my ML pipeline.
