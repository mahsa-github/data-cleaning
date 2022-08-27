# Data-cleaning_part-1_cat2cat
this repository consists of the data cleaning samples in python. Input and output are categorical and I have used Chi2 and Mutual information feature selection. the data set is "cancer data set" and the link is provided below. 
## Process in detail : 
1- Split the data into train and test using Train_test_split

2- Input and out put preparation using OrdinalEncoder and LabelEncoder 

3- Feature selection

3-1 Feature selection using Chi squared

3-2 Feature selection using Mutual Information

4- Modeling using selected features from last step

As the result we got different accuaracies base on the feature selection methods we used. we got the Accuracy: 76.84 by using Mutual information method and K=4
