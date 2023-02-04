# ATLIQ-Grands-project

## Problem

 `ATLIQ Grands` owns multiple five-star hotels across India. They have been in the `hospitality industry` for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management,  ATLIQ Grands are `losing its market share and revenue` in the luxury/business hotels category. As a strategic move, the managing director of  ATLIQ Grands wanted to incorporate “Business and Data Intelligence” in order to regain their market share and revenue.
 
 ## Task
 As a strategic move, the managing director of  ATLIQ Grands wanted to incorporate “Business and Data Intelligence” in order to regain their market share and revenue.You are a data analyst who has been provided with required data.So do the analysis and provide an insightful amazing dashboard to the stakeholders.

 # Solution steps
 ###### Cleaning and analysis was done using `SQL Server`, visualization using `Power BI`  and finally made a presentation using `Powerpoint` 
 ### Step 1. Description of the data
 ### Step 2. Feature engineering & Feature selection of the data
 ### Step 3. Analysis of the data
 ### Step 4. Visualization of the data 

 -----------
 
 ## Step 1. Description of the data
 
- Our database  has 5 differnt  CSV files
- `Dim_date` contains `date`,` mmm yy(monthname year)`,`week no`,`day_type( Weekend or Weekeday)`
-  `Dim_hotels` contains `Property_id`,`Property_name`,`Category`,`City`
-  `Dim_rooms` contains `room_id`,`room_class`
-  `Fact_aggregated_bookings` contains `property_id`,`check_in_date`,`room_category`,`successful_bookings`,`capacity`
- `Fact_bookings ` contains `booking_id`,`property_id`,`booking_date`,`check_in_date`,`check_out_date`,`no_guests`,`room_category`,`booking_platform`,`ratings_given`,`booking_status`,`revenue_generated`,`revenue_realized`
 --------------
 ## Step 2.Feature engineering & Feature selection of the data
 
 - After understanding the data we noticed that all `date formats ` are not in regular format and `ratings given` has more than 50% are nulls
 - Now date format updated from `2022-05-04 00:00:00.0000000` to `2022-05-04`
 - Similarly huge null values present in the `ratings_given` column they are replaced with `avg_hotel_rating` 
 -------------
 
  ## Step 3. Analysis of the data
  
  - Total analysis part was given in `ATLIQ Grands project analysis.sql` file
   --------------
 
 ## Step 4. Visualization of the data
 
 - Visit [here](https://app.powerbi.com/links/007fPQ3R2D?ctid=0c167956-3359-4be3-b187-477bb0785442&pbi_source=linkShare)
  --------------
  
  
  
  
## Key findings & Recomedations

- Out of the total generated revenue of 2008M, almost 200M revenue is lost through cancellations
- Mumbai generates highest revenue of 669M among all cities whereas delhi generates least revenue of 295M.So revenue management must focus on delhi city to boost the revenue
- When it comes to room class ,Ellite generates highest revenue of 560M whereas standard class generates revenue of 310M. So it is evident that customers chose more of medium range budget rooms.So by increasing the capacity of ellite rooms and decreasing the standard rooms will boost the revenue
- Among all properties Atliq exotica  generates highest revenue of 320M whereas Atliq seasons generates least revenue of 66M
- Week 21,23,26,30 has considerable drop in revenue  and in week 32 revenue dropped drastically
- Overall occupancy stands at 58% So, in order to increase the increase the revenue management should focus on increasing the occupancy rate across the hotels
- Total bookings are 135k out of all bookings 33K got cancelled ,so managementhas to take measures on to reduce the cancellations
- Delhi has highest rating 3.78 and highest occupancy 60.55% but it is generating least revenue 295M. 
-Overall average daily revenue(ADR) is 12.7k. ADR is nothing but average revenue generating by each room higher the ADR higher the revenue generated so management has to focus on ways to boost the ADR in order to incerase the overall revenue
- Overall revenue per available room(RevPAR) is 7.3K.RevPAR is a hospitallity industry performance measure it reflects the ability of a property to fill the available rooms at an average rate 
