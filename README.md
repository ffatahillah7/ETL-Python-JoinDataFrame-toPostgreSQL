# ETL-Python-JoinDataFrame-toPostgreSQL
ETL Transform dataset from joining two dataset Csv and Parquet to PostgreSQL

The purpose of this project is to extract dataset from csv and parquet file, transform with joining those two datasets using python pandasql and load to PostgreSQL.

Download Dataset file : 
-  https://drive.google.com/file/d/1_HWqRaBNmstHobqkIW2UypQXy6INMp04/view?usp=sharing
-  https://drive.google.com/file/d/1sTvhPbclo-s9mXGBnsX2W6NK1YnknAN3/view?usp=sharing

## Goals of the Project:

1.  Extract dataset from various files such as csv, excel, parquet, json, etc.
2.  Transform using python (I used jupyter notebook) and pandaSQL as Library. PandaSQL have a query like common query in SQL Languages on Python.
3.  Join The dataframe and filter it to specific values.  
4.  Load the result to PostgreSQL using SQLAlchemy library on Python.


## Materials and Methods

1.  Bussiness Understanding : The Business Understanding phase focuses on understanding the objectives and requirements of the project. In this project, we should know about what's happening, why it's happening and who is involved in the dataset.
2.  Data Understanding : Next is the Data Understanding phase. Adding to the foundation of Business Understanding, it drives the focus to identify, collect, and analyze the data sets that can help you accomplish the project goals. The data is consist of trip data and taxi service zone.
3.  Data Preparation : This phase, which is often referred to as “data munging”, prepares the final data set(s) for modeling. In this methods , we reading the data frame using dataframe head or subscribe. We make sure that the table, the columns and the data values are on right things. Filter with specific values, use unique function to knows the unique values.

## Lesson Results

1.  The trip data parquet and taxi service zone csv successfully extract from csv to panda dataframe on python. Using pd.read_csv and pd.read_parquet, pointed to your directory, we can read the dataset clearly.
2.  The transformation phase is to confirm the data, and check the column names, values ​​and data format.
3.  We can learn about join from two dataset and filter the result with specific columns value.
4.  We can learn about connection on The Load Phase. The connection build from dataframe to database, for this case is PostgreSQL, using to_sql code on python-pandas library. In this stage, we defined the table name, the connection name, and any other configuration such as if there is an existing table, what should we do?
