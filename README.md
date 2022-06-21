# Bike_Sharing_Visualization

## Objective
The purpose of this project is to use Tableau to visualize the citibike data.

### Tasks
1. Imported 201908-citibike-tripdata.csv file to Jupyter Notebook and convert to a Pandas DataFrame.
2. Check the DataFrame's columns for improper data types.
2. Used Python and Pandas to change the DataFrame's trip duration column to a datetime format.
3. Used Tableau Public to create visualizations for the trip analysis.
4. Created a story and report with Tableau Public for the final presentation.

## Resources

### Tools/Languages
- Tableau Public 2021.4.4
- Pandas 1.3.4
- Python 3.7.11
- Jupyter Notebook 6.4.5

### Sites/Data
- 201908-citibike-tripdata.csv
- trip_data.csv
- https://s3.amazonaws.com/tripdata/index.html

## Results
View my complete visualization here: [link to dashboard](https://public.tableau.com/app/profile/tiana5411/viz/CitiBikeData_16480896124550/CitiBikeStory) 

### Trips by Gender by Weekday

![trip-gender-weekday](https://user-images.githubusercontent.com/33010018/160217025-2d22cc3d-1729-4594-8ee8-10973a71723d.png)

Most subscribers are male and Thurday is the most used day for male subscribers.  Female customers mostly use the service on Saturday and Sunday.

### Trips by Gender by Weekday Per Hour

![trips-by-gender-by-weekday](https://user-images.githubusercontent.com/33010018/160217160-dc08a541-6577-46fd-8152-f3767ff867c6.png)

Most trips occur between 6AM-9AM and 5PM-8PM for each day of the week.

### Trips by Weekday for Each Hour

![trips-weekday-hour](https://user-images.githubusercontent.com/33010018/160217352-8360d9dd-dcb3-41b6-a5b3-1e0faa0be040.png)

The most trips occur on Thursday around 6PM.

### Checkout Times by Gender

![Screen Shot 2022-03-25 at 8 34 56 PM](https://user-images.githubusercontent.com/33010018/160217490-171c4601-0bfa-484c-b875-28c0571c9687.png)

Males have the highest tripduration with a peak at 5 hours.

### Checkout Times for All Users

![checkout-for-all](https://user-images.githubusercontent.com/33010018/160217806-8aeddc31-239f-4032-a592-1b17b6c67643.png)


The longest checkout time for all users is around 5 hours.

### August Peak Hours

![Screen Shot 2022-03-25 at 8 47 11 PM](https://user-images.githubusercontent.com/33010018/160217923-c621885e-dc7b-41d8-855e-060e365009b5.png)

The highest user count is around 220K and the peak hour is 5PM.

### Bike Utilization

![Screen Shot 2022-03-25 at 8 50 40 PM](https://user-images.githubusercontent.com/33010018/160218038-64a81761-174c-49a2-b247-d1f0a9765af6.png)


The bike with the most tripduration has almost 4 million trips.


## Summary

The most utilization occurs on weekdays when people are either going to or leaving work. Bike maintenance should occur between work hours when there is less utilization.   Males appear to mostly use the service and also take longer trips.  More research should be done on why females are less likely to subscribe to the service.


### Additional Visualizations

- Age of Users

![Screen Shot 2022-03-25 at 9 10 36 PM](https://user-images.githubusercontent.com/33010018/160218739-bd71a88f-4b90-43d7-90f1-f39d8441200c.png)

The most users were born in 1969.  However, the next group of users were born in the late 80s and early 90s.

- Age vs Gender

![Screen Shot 2022-03-25 at 9 17 44 PM](https://user-images.githubusercontent.com/33010018/160218992-9e447521-bda1-4b8d-8de2-99e68c844b03.png)

Most of the older users are female.





