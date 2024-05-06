# UberPickupsInNewYorkCity-Tableau
![Alt Text](URL)
![Alt Text](URL)
![Alt Text](URL)

## Introduction
Welcome to the Uber Data Analysis Tableau project! This project aims to analyze and visualize data related to Uber rides using Tableau. By leveraging interactive dashboards and visualizations, we can gain insights into various aspects of Uber operations, including ride patterns, driver behavior, customer demographics, and traffic trends.
## Data Sources
The data used in this project is sourced from various reputable sources, including:
Uber: Provides access to anonymized ride data for analysis purposes.
Public Transportation Authorities: Offers data on public transit routes, schedules, and traffic conditions.
## Features
1. Ride Patterns and Demand Analysis- Explore ride patterns and demand trends across different times of the day, days of the week, and geographic locations. Analyze factors such as peak hours, ride durations, and popular pickup and drop-off locations.
2. Driver Performance and Efficiency-Visualize driver performance metrics, including trip completion rates, average trip distances, and driver ratings. Identify top-performing drivers and areas for improvement in driver efficiency and customer satisfaction.
3. Traffic and Route Optimization-Visualize traffic patterns and congestion levels in different areas to optimize route planning and minimize ride durations. Analyze factors such as traffic volume, average speeds, and road closures to improve driver efficiency and customer satisfaction.
## Analysis
1. Cleaned the data by removing all the null values in excel itself. Created a separate excel sheet for all places where pick ups have been scheduled for different base numbers.
2. After creating the data for places and where pickups have been scheduled in which month and time I created another excel sheet where all the latitudes and longitudes are given from all months in a single sheet for easy data visualisation in tableau.
3. Now to create tableau representation of whole the data we will add those files and create a relationship by calculation.
4. Now in 1st sheet we will solve the first question given to us that is to find out month with highest uber pickups. For this question we will drag the base numbers in columns and also drag it to filters and choose show filters to see it on the sheet. From the sheet we will choose the drop-down menu option so that we can choose the base numbers according to our wish from the drop-down menu.
5. Then we will drag the date/ time of the uber pickups to columns and change it to month wise. We will also drag it to colours to see different colours for different months.
6. Then the number of trips information gathered together is dragged to rows. We will also drag it to Text under mark so that we can see count of number of trips in that month. From show up we will choose the graph representation.
7. Now in the 2nd sheet we will solve the next question that is to choose the weekday of the month with highest number of pickups.
8. We will remove the tooltip options for this question as it is not needed as we can see the number of trips written above the graphs.
9. For this question, we will drag the base numbers in rows and then in filters and show the filters and change it to single drop down so that we can choose the base numbers from the drop down.
10. Then we will drag the date/time to rows and change it to weekday to see the weekday’s number of trips. We will also drag it to colours so that we can see different weeks in different colours
11. Now we will drag number of trips to columns and detail to see its count of number of trips
12. Next sheet is for the visualisation to see the busiest times for uber pick ups in New York City. In this first we will drag the date/time to rows and change it to hours and drag number of trips count to columns.
13. We will change the visualisation to pie chart to see the timings from pie which has highest number of trips.
14. In next sheet we will see number of trips on hourly basis in text visualisation.
15. We will follow same steps for dragging the data/time in rows and changing it to hours and dragging count of number of trips to columns to see number of trips for every hour.
16. Next sheet is to see number of active vehicles for each base numbers. For this we will drag sum of active number of vehicles to the rows and base numbers to the column.
17. We will also drag these headings to text to see their details in the sheet.
18. For this question we will choose packed bubbles visualisation from show me.
19. Now in sheet number 6, we will visualise the next question that is busiest location for the uber pickups in New York city.
20. For this we will drag the address part of the data to rows and number of trips on the basis of its date on columns and from tree map from show me we can visualise the busiest location. We will drag address to text detail to see name od locations in New York city where most uber pickups have been scheduled.
21. Now next sheet is for the question for trips per hour, we will drag date/time to columns and change it to hours so that we could see the data on the basis of hours.
22. Then we will drag no. of trips data to rows to see the number of trips in each hour.
23.From show me we will change the visualisation to line graph to see the changes in growth of trips per hour or its decrease. Also, we will drag number of trips data to text detail to see its numbers.
24. In next sheet we need to visualise trips per week, so this time also we will drag date/time to columns and now we will change it to weekday from dropdown to see the number of trips changes along the week.
25. Then we will drag number of trips data to rows and from show me change it to line graph visualisation.
26. In this sheet also we will drag the number of trips data to text detail to see its data on the sheet itself.
27. In next sheet for trips per month we will follow same steps as we had done for trips per hour and trips per week. Just the difference is we will change the date/time value to month to see the changes in number of trips month wise.
28. In next sheet we have visualise the heat map of number of trips per hour, in this case we change the date/time value to hour and number of trips to rows and from show me change it to heat map visualisation.
29. After the visualisation we will select the range of sizes for number of trips and then according to it square boxes will be shown that is for higher number of trips during that particular hour bigger box will be shown and for smaller numbers smaller one and accordingly each hour is substituted with the square boxes according to number of trips.
30. In next sheet we need a heat map visualisation of trips per month so it has same procedure just the difference is we need to select month from drop down of date/time when we drag it in the sheet.
31. In next sheet map visualisation of new York city is shown with all its location where uber pick ups are there and where it is located can be visualised by dragging longitude and latitude of each address to rows and columns and address in detail to see location of each address to their corresponding latitude and longitude.
DASHBOARD VISUALISATIONS-
1. For 1st dashboard, I dragged sheet 1 to 5  and aligned them accordingly.
2. Then I created an action for sheet 1 and 2 for filtering the values whose base number have been selected for sheet 1 graph.
3. Then I created another action for highlighting the values between sheet 3 and 4 in which when we click any time from sheet 3 visualisation from pie chart its portion will be highlighted.
4. In sheet 1, I imported background from net by saving it first and them importing in the dashboard 1 through background maps.
5. Now in another dashboard we will drag the 6th sheet which is tree map visualisation of locations. 
6. For moving from dashboard 1 to dashboard 2 we created a navigation button so as when we will select that button it will navigate us to dashboard 2.
7. 8. In 3rd dashboard we will drag sheet 7,8,9,10 and 11 and align them. 
We will create 2 highlight actions for this dashboard, first for sheet 7 and 10 and another sheet 8 and 11 in which when we will select any hour( in case of sheet 7) and month (in case of sheet 8) its square block from heat map visualisation will be highlighted.
9. To got from dashboard 2 to 3 we created a navigation text so that when we will click at that text, we will be navigated to that dashboard.
10. We will create another action of going to sheet 12 to see the map visualisation of the location from dashboard 3 and same to come back to dashboard 3 we need to click any location.
11. We will create another navigation button of home to go to the start of the presentation.

## Contact Information
For inquiries or support regarding this project, please contact Arsh Zehra at zehrarsh@gmail.com.
