# Analysis of used cars data and hashtag data in twitter using spark in HDP and jupyter notebook.

# TECHNOLOGIES USED 
* APACHE 
* SPARK
* HDFS
* SPARK SQL
* JUPYTER NOTEBOOK
* PYTHON
* HIVE

# PROBLEM STATEMENT :
We are having a data set of used cars . We need some insights from the data set and the insights we needed are  given below. And also we some analysis on some hashtags data in twitter . The hashtags and the insights were given below.

# DESCRIPTION : 
* Took 'used cars' dataset from kaggele.
* Loaded the data set into sandbox as a CSV file.
* Loaded the data into a data frame and did some functions on the data set.
* By creating a temporary table performed some SQL queries on the table.
* Created our own data on hashtags data using tweepy library from twitter.
* Using jupyter performed some dataframe functions on the created dataset.
* Also used spark SQL on the created data to analyze.

# INSIGHTS : 
* The highest price and the lowest price of the cars.
* Region having the highest number of cars.
* Cars which are manufactured by Mercedes-Benz or Ferrari and  black in color.
* Cars whose manufacturer name starts with name ‘m’ and price more than 100000.
* We need a new column which has the fields two times of its price.
* Rename the column ‘odometer’ of our data set to ‘odometer value’.
* Count of cars from region “auburn” which covered a distance greater than  70000.
* Region where the models ‘f-150’ or ‘compass’ , ‘Tacoma’ were available in black color. 
* Data of manufacturer ,model , transmission where price is greater than 50000.
* Model of the car which was purchased mostly.
