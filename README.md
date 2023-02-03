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
 ### Step 5. Presentation to stakeholders
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
  ## Step 5. Presentation to stakeholders
  
  
  - Total Presentation part was given in `Presentation.ppt` file
  --------------
## Key findings

➽ 𝗢𝘂𝘁 𝗼𝗳 𝘁𝗵𝗲 𝘁𝗼𝘁𝗮𝗹 𝗴𝗲𝗻𝗲𝗿𝗮𝘁𝗲𝗱 𝗿𝗲𝘃𝗲𝗻𝘂𝗲 𝗼𝗳 𝟮𝟬𝟬𝟴𝗠,𝗮𝗹𝗺𝗼𝘀𝘁 1𝟵𝟵𝗠 𝗿𝗲𝘃𝗲𝗻𝘂𝗲 𝗶𝘀 𝗹𝗼𝘀𝘁 𝘁𝗵𝗿𝗼𝘂𝗴𝗵 𝗰𝗮𝗻𝗰𝗲𝗹𝗹𝗮𝘁𝗶𝗼𝗻𝘀.

➽ 𝗠𝘂𝗺𝗯𝗮𝗶 𝗴𝗲𝗻𝗲𝗿𝗮𝘁𝗲𝘀 𝗵𝗶𝗴𝗵𝗲𝘀𝘁 𝗿𝗲𝘃𝗲𝗻𝘂𝗲 𝗼𝗳 𝟲𝟲𝟵𝗠 𝗮𝗺𝗼𝗻𝗴 𝗮𝗹𝗹 𝗰𝗶𝘁𝗶𝗲𝘀 𝘄𝗵𝗲𝗿𝗲𝗮𝘀
𝗗𝗲𝗹𝗵𝗶 𝗴𝗲𝗻𝗲𝗿𝗮𝘁𝗲𝘀 𝗹𝗼𝘄𝗲𝘀𝘁 𝗿𝗲𝘃𝗲𝗻𝘂𝗲 𝗼𝗳 𝟮𝟵𝟱𝗠.

➽ 𝗪𝗵𝗲𝗻 𝗶𝘁 𝗰𝗼𝗺𝗲𝘀 𝘁𝗼 𝗿𝗼𝗼𝗺 𝗰𝗹𝗮𝘀𝘀 , 𝗘𝗹𝗶𝘁𝗲 𝗴𝗲𝗻𝗲𝗿𝗮𝘁𝗲𝘀 𝗵𝗶𝗴𝗵𝗲𝘀𝘁 𝗿𝗲𝘃𝗲𝗻𝘂𝗲 𝗼𝗳 𝟱𝟲𝟬𝗠 𝘄𝗵𝗲𝗿𝗲𝗮𝘀 𝘀𝘁𝗮𝗻𝗱𝗮𝗿𝗱 𝗰𝗹𝗮𝘀𝘀 𝗴𝗲𝗻𝗲𝗿𝗮𝘁𝗲𝘀 𝗿𝗲𝘃𝗲𝗻𝘂𝗲 𝗼𝗳 𝟯𝟭𝟬𝗠. 𝗦𝗼 𝗶𝘁 𝗶𝘀 𝗲𝘃𝗶𝗱𝗲𝗻𝘁 𝘁𝗵𝗮𝘁 𝗰𝘂𝘀𝘁𝗼𝗺𝗲𝗿𝘀 𝗰𝗵𝗼𝘀𝗲 𝗺𝗼𝗿𝗲 𝗼𝗳 𝗺𝗲𝗱𝗶𝘂𝗺 𝗿𝗮𝗻𝗴𝗲 𝗯𝘂𝗱𝗴𝗲𝘁 𝗿𝗼𝗼𝗺𝘀 .

➽ 𝗪𝗲𝗲𝗸 𝟮𝟭, 𝟮𝟯 ,𝟮𝟲 𝗮𝗻𝗱 𝟯𝟬 𝗵𝗮𝘀 𝗮 𝗰𝗼𝗻𝘀𝗶𝗱𝗲𝗿𝗮𝗯𝗹𝗲 𝗱𝗿𝗼𝗽 𝗶𝗻 𝗿𝗲𝘃𝗲𝗻𝘂𝗲.

➽ 𝗢𝘃𝗲𝗿𝗮𝗹𝗹 𝗼𝗰𝗰𝘂𝗽𝗮𝗻𝗰𝘆 𝘀𝘁𝗮𝗻𝗱𝘀 𝗮𝘁 𝟱𝟴%.
