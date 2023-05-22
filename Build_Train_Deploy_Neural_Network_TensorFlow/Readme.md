# [build-train-deploy-first-neural-network-tensorflow](https://app.pluralsight.com/library/courses/build-train-deploy-first-neural-network-tensorflow/table-of-contents)

## Colab tips
 - To enable interactive tables: use `data_table.enable_dataframe_formatter()` this will allow interactive mode where one can search, sort etc

eg:- 
 ```
import pandas as pd
df_housing = pd.read_csv(csv_housefile)

from google.colab import data_table
data_table.enable_dataframe_formatter()

display(df_housing)
 ```
 > This will display the table in an interactive mode making it easier to explore and analyze dataframes, including:

* Pagination: The data_table formatter supports pagination, which allows you to view the data in the dataframe one page at a time.
* Sorting: The data_table formatter allows you to sort the data in the dataframe by any column.
* Searching: The data_table formatter allows you to search for specific values in the data.
* Filtering: The data_table formatter allows you to filter the data in the dataframe based on a variety of criteria.
 - Check python version in colab
 ```
 !python --version
 ```
 
* [github - JerryKurata/First-NN-Tensorflow](https://github.com/JerryKurata/First-NN-Tensorflow)
