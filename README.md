# Tweet_analysis
Tweet analysis during hurricane ian using nlp techniques
The following data is having the person’s credit related information and how the credit score is
classified based on the parameters of the data. The data is having 28 features with credit score as
target variable. Initially the cleaning of the data is done by the different cleaning methods available
in the pandas. Most of the data types are in object type were converted to numerical. Converted all
the categorical data into numerical by using the pandas dummies method. The credit score range
is having 3 types with good, standard, poor and changed them to good-0, standard-1, poor-2. The
outliers are removed using the IQR method and all the correlation coefficients are calculated
between the features. The feature selection and PCA methods are applied on the dataset to select
the top 10 features from the dataset. The PCA method is applied to reduce the number of features
for less complexity process. The 5 Machine Learning Algorithms applied in the 2 methods for the
dataset. The dataset is divided into training, testing and validation and after applying MinMax
Scaling the hyper parameter validation done using the validation dataset using grid search and
randomized search methods to select the best method. The Evaluation metrics are calculated for
the all the best methods that derived from the hyper parameter validation.
