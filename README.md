# Diamonds---Price-prediction

imported the dataset from Kaggle
studied the landscape
dropped insignificant columns like Index
There were no null values
Studied the statistics of the dataframe. It seemed ok
convert categorical to binary vectors
find out pairwise correlation
find out vif. now there were attributes for which VIF is more than 5. however if we have a look at those attributes in correlation matrix; then we see that those attributes have a high correlation with price. Hence, i decide not to remove those attributes
Run various models
