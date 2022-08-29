## Data-cleaning
this repository consists of the data cleaning samples in python. Input and output are categorical and I have used Chi2 and Mutual information feature selection. the data set is "cancer data set" and the link is provided below. 
## Process in detail_part 1 _ category input category output : 
1- Split the data into train and test using Train_test_split

2- Input and out put preparation using OrdinalEncoder and LabelEncoder 

3- Feature selection

3-1 Feature selection using Chi squared

3-2 Feature selection using Mutual Information

4- Modeling using selected features from last step

As the result we got different accuaracies base on the feature selection methods we used. we got the Accuracy: 76.84 by using Mutual information method and K=4


## Process in detail _ part 2 _ Numerical input , Category output
In this section the process and the steps are almost the same as Cat2Cat but this time the feature selection methods are different. feature Selection method is using Anova and Mutual information feature selection. 


## Process of data leakage 

In a very simple language, when we use test set to train the model or even preprocess the data, data leakage is happening. As part of my experience I have checked the wrong way and the correct way of prediction.
