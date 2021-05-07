# Ford-GoBike Exploration 
This exploration is done on the ford go-bike dataset
## Ford-GoBike Data Set
There are 183412 trip rides in the dataset with 16 features (duration_sec, start_time, end_time , start_station_id, start_station_name, start_station_latitude, start_station_id, start_station_longitude, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip  ). Most variables are numeric in nature, but the variables start_time and end_time are date & time and the variables start_station_name, end_station_name, user_type, member_gender are object type and finaly the bike share for all trip feature is of type boolean
## Methadology
the methadology used working on this dataset was trying to find relation between the features of the dataset and the duration featrue to try to find patterns that might affect duration first was try to get a month and day to try to see how the rides differ depending on the day and month but the dataset provied was all collected on the same day, so we setteld on using the gender, age, age_group and user type to try find patterns that might help us understand what affect duration taken in every ride

## Prerequisites
Anaconda
Python 
Pandas
Numpy
Matplotlib
Seaborn

## Conclusion
after exploring the data set it was clear that age group of youth and adults had the longest duration taking tripes and that the gender didnt affect the duration also distance had a wierd relationship with duration