# Data-Analysis-Project
We have two datasets here, one is Data.csv which contains columns like order_id, de_id, placed_time, delivered_time, customer_zone etc which explains about when the order is placed, at what place, whether the order is accepted by delivery partner or not etc.
Other dataset we have is Delivery_Partners_Data.csv which contains columns like de_id, shift_end_time, de_joining_date etc explaining about ID of the delivery guy, shift ending time of the delivery guy, zone of the delivery guy etc.

With the help of those features I performed Exploratory Data Analysis where we plotted several plots using matplotlib and seaborn. I've also Data Preprocessing and Data Cleaning using tools like Pandas and Numpy where I cleaned the data, Performed Feature Extraction, Created new features and Imputing the missing values.

Lastly using Sklearn I trained a Random Forest model, which identifies the correct delivery partner with which the order should be given with 96% Accuracy.
