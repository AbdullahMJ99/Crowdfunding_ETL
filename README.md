# Crowdfunding_ETL
Crowdfunding_ETL
For the ETL mini project, you will work with a partner to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After you transform the data, you'll create four CSV files and use the CSV file data to create an ERD and a table schema. Finally, you’ll upload the CSV file data into a Postgres database.

Since this is a one-week project, make sure that you have done at least half of your project before the third day of class to stay on track.

Although you and your partner will divide the work, it’s essential to collaborate and communicate while working on different parts of the project. Be sure to check in with your partner regularly and offer support

A Category DataFrame is Created

A Subcategory DataFrame is Created

A Campaign DataFrame is Created

A Contacts DataFrame is Created

A Crowdfunding Database is Created

Data columns (total 15 columns):

Column Non-Null Count Dtype
0 cf_id 1000 non-null int64
1 contact_id 1000 non-null int64
2 company_name 1000 non-null object
3 blurb 1000 non-null object
4 goal 1000 non-null int64
5 pledged 1000 non-null int64
6 outcome 1000 non-null object
7 backers_count 1000 non-null int64
8 country 1000 non-null object
9 currency 1000 non-null object
10 launched_at 1000 non-null int64
11 deadline 1000 non-null int64
12 staff_pick 1000 non-null bool
13 spotlight 1000 non-null bool
14 category & sub-category 1000 non-null object dtypes: bool(2), int64(7), object(6) memory usage: 103.6+ KB
Contacts dataframe datatypes Option 1 <class 'pandas.core.frame.DataFrame'> RangeIndex: 1000 entries, 0 to 999 Data columns (total 4 columns):

Column Non-Null Count Dtype
0 contact_id 1000 non-null int64
1 first_name 1000 non-null object
2 last_name 1000 non-null object
3 email 1000 non-null object dtypes: int64(1), object(3) memory usage: 31.4+ KB
Option 2 <class 'pandas.core.frame.DataFrame'> RangeIndex: 1000 entries, 0 to 999 Data columns (total 4 columns):

Column Non-Null Count Dtype
0 contact_id 1000 non-null int32
1 first_name 1000 non-null object
2 last_name 1000 non-null object
3 email 1000 non-null object dtypes: int32(1), object(3) memory usage: 27.5+ KB
Databases created with Python, pandas, excel and jupyter notebook.
