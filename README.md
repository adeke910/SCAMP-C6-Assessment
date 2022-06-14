# SCAMP-C6-Assessment
Data Science Technical Assessment
## DESCRIPTION
The given dataset contains a collection of job postings, some of which are fraudulent. The data contains textual & meta info about these jobs. 
Studied the details of the dataset to find the  industry with the highest number of fake job postings. 
## Python libraries used:
- Numpy
- Pandas
- Seaborn
- Matplotlib
### Visualisations
- **Bar Plots:** Classical bar plots that are good for visualisation and comparison of different data statistics, especially comparing statistics of feature variables.
### Pandas Data Science

#### Basic Dataset Information
- **Read in a CSV dataset:** `pd.DataFrame.from_csv("csv_file")` OR `pd.read_csv("csv_file")`
- **Basic dataset feature info:** `fake_job_df.info()`
- **Basic dataset statistics:** `fake_job_df.describe()` 

#### Basic Data Handling
- **Drop missing data:** `df.dropna(axis=0, how='any')` Return object with labels on given axis omitted where alternately any or all of the data are missing
- **Replace missing data:** `df.replace(to_replace=None, value=None)` Replace values given in "to_replace" with "value".
- **Check for NANs:** `pd.isnull(object)` Detect missing values (NaN in numeric arrays, None/NaN in object arrays)
- **Get first "n" rows:** `df.head([n])`

