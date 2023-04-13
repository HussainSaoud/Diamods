# Diamods
I'm Happy to share my first competition on kaggle with SHAI For AI | شاي للذكاء الاصطناعي  to Predict Diamond Price
after loading the Data and take a quick look on the Context
- the first step was Discover and Visualize the Data to Gain Insights :
explore missing data ,correlations between features , Identifying outliers
- the second step is Prepare the Data for Machine Learning Algorithms :
this step conatin :
1-Cleaning the data :
remove outliers and faulty values , fill null values with the median
2- Encoding categorical variables with OrdinalEncoder
3- Feature Scaling with StandardScaler
-Build and Fine-Tune :
after trying many Algorithms I choose Random forest and Grid search

RMSE with cross-validation : 566.86

technologies and libraries :
Python ,numpy ,pandas , matplotlib , seaborn , Scikit-learn , Google Colab
# diamonds_project.ipynb
a google colab notebook contain EDA and the model building 
# train.csv
traning dataset
# test.csv
testing dataset
