# Weather-Analysis
Nature Experimentation

# Here, the weather dataset is a time-series data set with per hour about the weather conditions at a particular location. It records Temperature, Dew Point Temperature, Relative Humidity, Wind Speed, Visibility, Pressure, and Conditions.

How to Analyze DataFrames ?

.head()
It shows the first N rows in the data (by default, N=5).

.shape
It shows the total no. of rows and no. of columns of the dataframe

.index
This attribute provides the index of the dataframe

.columns
It shows the name of each column

.dtypes
It shows the data-type of each column

.unique()
In a column, It shows all the unique values. It can be applied on a single column only, not on the whole dataframe

.nunique()
It shows the total no. of unique values in each column. It can be applied on a single column as well as on whole dataframe.

.count
It shows the total no. of non.null values in each column. It can be applied on a single column as well as on whole dataframe

.value_counts
In a column, it shows all the unique values with their count, it can be applied on single column only.

.info()
Provides basic information about the dataframe.

https://colab.research.google.com/drive/1qE7JGtOba4KQ8-iAPh2rbDZQP2or1n2e#scrollTo=Q1_Find_all_the_unique_Wind_Speed_values_in_the_data_

