# Hotel-Booking-Analysis-EDA-
## Project Summary ---->>>>>
In this project we began to explore the dataset in which Hotel Booking comprises of two types of hotels i.e City Hotel and Resort Hotel.

In this dataset, there are 119390 rows and 32 columns.

All the columns are divided into three dtypes : Object, float64 and int64.

In this dataset, there are both duplicates and missing values available. So, we have to deal with that and as a result i have replaced the null and missing values and also i dropped the duplicate values.

The maximum number of missing values are from 'Company' column then followed by 'Agent','Country' and 'Children' columns. The 'Children' column consists of only 4 null values while 'Company' column consists of 112593 null values.

In this project, i divided the data manipulation workflow into three categories i.e. Data Collection, Data cleaning & manipulation and EDA(Exploratory Data Analysis).

In moving further, i have used various basic functions and attributes i.e Data collections first step to find different columns which is done by various methods like Head(), tail(), info(), describe(), columns() and some others method used for data collections.

As i further moved, i check the number of unique values of each columns and generate a list of those values and then also find the unique values of each columns later on.

Then further i converted the datatypes of columns into appropriate datatype. I added some of the columns name here, one is 'total_people' and other is 'total_stay'.

Find some columns are not in accurate data types which correct it later, done in Data cleaning part and as well as duplicates data items must be removed as i find duplicate items equal to 31994 which is dropped from dataset later.

I found that there were some rows in which the combining values of adults, babies and childrens was 0, so this simply means there were no guests as 0 indicates presence of none. So, there were no bookings made. As a result, i simply dropped the rows where combining values of adults, babies and children columns was 0.

The data type of 'reservation_status_date' column was object type, so it was changed to date type format for better use.

Before visualizing any data from the data set we have to do data wrangling. For that, i have checked the null value of all the columns. After checking, when i find minimal number of null values, filling these null values with necessary values as per requirement by using fillna().

So, after completing the process of data wrangling, i moved to the data visualization part.

In the data visualization process, i have used various charts and have dived deep understanding the graphs to catch the proper insights from the data. That gives the business outcomes which will ultimately boost the businesses.

So, i explored and analyzed the data to discover important factors that govern the bookings.
parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyze the data to discover important factors that govern the bookings.

Define Your Business Objective?
