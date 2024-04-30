# Project-
# Data-Wrangling-project-2
Data Acquisition and data Wrangling using Pandas and NumPy library
Data Acquisition & Wrangling

Data Acquisition & Wrangling: This involves obtaining raw data from various sources and then cleaning, restructuring, and preparing it for analysis. It
encompasses tasks like handling missing values, dropping irrelevant data, and merging datasets.
Data head:Find the top value.
Data tail:Find the bottom value.
The data type datetime64[ns]:It is the standard representation of dates and times in Pandas. When you perform data wrangling operations such as converting a column containing date or time information to datetime objects using pd.to_datetime(), Pandas automatically assigns the datetime64[ns] data type to the resulting column.
Data isnull: The isnull() function identifies missing values in a dataset, returning a boolean mask indicating whether each value is null
Data.notnull:The primary purpose of using dataset_2.notnull() is to identify which values in the DataFrame dataset_2 are not null. This can be useful for various data wrangling tasks where you need to handle missing or null values differently from non-null values
Missing Values: Identifying and handling missing values is crucial for data analysis. Techniques include imputation (filling missing values with estimated ones) or removing rows/columns with missing values.
Data Drop: Dropping data refers to removing rows or columns from a dataset, often to eliminate irrelevant or redundant information.
Data Unique: Finding unique values in a dataset helps identify distinct categories or entities within the data.
Data Types (Data Dtypes): Understanding the data types of variables in a dataset is essential for proper data manipulation and analysis.
Data Merge: Merging datasets involves combining multiple datasets into one based on common attributes or keys.
skewness:Skewness is a statistical measure used to describe the asymmetry or lack of symmetry in the distribution of a dataset. It helps in understanding the shape of the distribution and whether it is symmetric or skewed to one side.
Correlation:Correlation is a statistical measure used to quantify the strength and direction of the relationship between two variables.
Data Describe: The describe() function provides summary statistics for numerical variables in a dataset, such as mean, median, minimum, maximum, and quartiles.
Data Outlier: Outliers are data points that significantly differ from other observations. Identifying and handling outliers is crucial to prevent them from skewing analysis results.
Data Fill: Filling missing values in a dataset involves replacing them with specific values, such as the mean, median, or mode of the respective column.
Data astype: The astype() method is used to convert the data type of one or more columns in a DataFrame.
Boxplot: A box plot (or box-and-whisker plot) is a graphical representation of the distribution of data through quartiles.
Find Mean, Mode, Median: These are measures of central tendency used to describe the central position of a set of data values
fillna:The fillna function in pandas is used to fill or replace missing (NaN) values in a DataFrame or Series with a specified value. Here are some reasons why fillna is commonly used in data analysis:
Imputaion Method:Imputation methods are techniques used to replace missing or incomplete data values in a dataset with estimated values. These estimated values are typically derived from the observed data or based on certain statistical assumptions. Imputation is an essential step in data preprocessing to ensure that missing values do not affect the integrity or analysis of the dataset.
