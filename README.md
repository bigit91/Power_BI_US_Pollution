# US Pollution Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/75040cfd-cb68-49ce-999f-4f51f7dd904d/ReportSection?experience=power-bi

## Problem Statement :
Analyse U.S Pollution dataset and make informative output out of it.  

US Pollution:
Air pollution is the contamination of air due to the presence of substances in the atmosphere that are harmful to the health of humans and other living beings, or cause damage to the climate or to materials.
This dataset provides you the pollution in the U.S. It contains daily data for the four major pollutants NO2, O3, SO2 and CO each has 5 specific columns during 2006 and 2010. 

Abbreviations: Carbon Monoxide (CO), Ozone (O3), Sulphur Dioxide (SO2), Nitrogen Dioxide (NO2) The four pollutants (NO2, O3, SO2 and O3) each has 5 specific columns. 
●	State names:  Lists of state names in US
●	State code: Code numbers belongs to each state
●	County code: Unique code numbers specified for county
●	Site number: numbers given to the sites
●	Address: The Address of each locality where pollutant has been detected
●	Country names: List of county names
●	City names: Names of city 
●	Date local: Day Month and the year of every local area when pollutant took place and the hierarchy
●	NO2 units: Units represented by Parts Per Billion, NO2 mean, NO2 1st MAX value, NO2 1st MAX hour, NO2 AQI
●	O3 units: Units represented by parts per million, O3 mean, O3 1st MAX value, O3 1st MAX hour, O3 AQI
●	SO2 units: Units represented by Parts Per Billion, SO2 mean, SO2 1st MAX value, SO2 1st MAX hour, SO2 AQI
●	CO units: Units represented by parts per million, CO2 mean, CO2 1st MAX value, CO2 1st MAX hour, CO2 AQI

NOTE: Replace all null values to 0
After understanding/visualizing the data, design a report for the U.S Pollution review information. Make sure to create interactive insights.

### Below are the information/demands to be performed in desktop in order to meet requirement:

Page 1: Overview
●	Create text boxes to display all 4 category pollutants and give the action-page navigation.
●	Create Slicers to display states, cities,  counties and so on...
●	Need only the years which has been affected by pollution (you can use a slicer)
●	Create a filled map to show only US States
●	Generate a table display county names along with codes
●	Create Quarter-wise bifurcation of all 4 pollutants. 


Page 2: [Name as Carbon Monoxide] for page navigation and create these below things
Carbon monoxide is a colourless, highly poisonous, odourless, tasteless, flammable gas that is slightly less dense than air.
●	Top 10 states with highest CO pollutants
●	Find out the 1st maximum hour for CO and use the card
●	Find out the 1st maximum value for CO, use a card
●	Use a card and show the CO units been calculated per
●	Create a table to show the Carbon Monoxide present in AQI for each state codes and display the highest in RED, lowest In GREEN by applying settings to background
●	Create a chart to display Maximum CO present in each state
●	Get the CO in AQI for each year show it using line chart
●	Find the top 1 CO pollutant city present in air
●	Add a slicer to display states which can be interactive with these pollutants
●	Use Sync Slicer to select the range(date) and find out the highest, lowest pollutants and maximum Carbon Monoxide available in air


Page 3: [Name as Ozone] for page navigation and create these below things
Ozone is a gas. High in the atmosphere, it protects us from UV radiation. But at ground level, ozone is a pollutant.
●	Top 10 states with highest O3 pollutants
●	Find out the 1st maximum hour for Ozone and use the card
●	Find out the 1st maximum value for Ozone, use a card
●	Use a card and show the Ozone units been calculated per
●	Create a table to show the Ozone present in AQI for each state codes and display the highest in RED, lowest In GREEN by applying settings to background
●	Create a chart to display Maximum O3 present in each state
●	Get the O3 in AQI for each year show it using line chart
●	Find the top 1 O3 pollutant city present in air
●	Add a slicer to display states which can be interactive with these pollutants
●	Use sync Slicer to select the range(date) and find out the highest, lowest pollutants and maximum Ozone available in air

Page 4: [Name as Sulphur Dioxide] for page navigation and create these below things
Sulphur dioxide is a gas. Breathing it in can irritate your nose, throat and lungs. Sulphur dioxide is a common air pollutant.
●	Top 10 states and cities with highest SO2 pollutants
●	Find out the 1st maximum hour for Sulphur Dioxide and use the card
●	Find out the 1st maximum value for Sulphur Dioxide, use a card
●	Use a card and show the Sulphur Dioxide units been calculated per
●	Create a table to show the Sulphur Dioxide present in AQI for each state codes and display the highest in RED, lowest In GREEN by applying settings to background
●	Create a chart to display Maximum SO2 present in each state
●	Get the SO2 in AQI for each year show it using line chart
●	Find the top 1 SO2 pollutant city present in air
●	Use Sync Slicer to select the range(date) and find out the highest, lowest pollutants and maximum SO2 available in air
●	Add a slicer to display states which can be interactive with these pollutants


Page 5: [Name as Nitrogen Dioxide] for page navigation and create these below things
NO₂ is an intermediate in the industrial synthesis of nitric acid, millions of tons of which are produced each year for use primarily in the production of fertilizers. 

●	Top 10 states with highest NO2 pollutants
●	Find out the 1st maximum hour for Nitrogen Dioxide, use the card
●	Find out the 1st maximum value for Nitrogen Dioxide, use a card
●	Use a card and show the Nitrogen Dioxide units been calculated per
●	Create a table to show the Nitrogen Dioxide present in AQI for each state codes and display the highest in RED, lowest In GREEN by applying settings to background
●	Create a chart to display Maximum NO2 present in each state
●	Get the NO2 in AQI for each year show it using line chart
●	Use Sync Slicer to select the range(date) and find out the highest, lowest pollutants and maximum Nitrogen Dioxide available in air
●	Add a slicer to display states which can be interactive with these pollutants

You can add as much as information on your report by using this data. 
Note: Remember that the visuals should be relevant      


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : It was observed that in none of the columns had  errors but there were some null values which were replaced by zeroes 0 as suggested by stakeholder
- Step 4 : In the report view, under the view tab, theme was selected . along with it Canvas background was selected in the Format Section of the Visualizations Pane
- Step 5 : We Start with the  Overview
			1) Wherein we create "Page Navigation Buttons" for all the 4 report pages  namely "Carbon Monoxide(CO),"Ozone(O3)","Sulphur Dioxide (SO2) AND "Nitrogen Dioxide (NO2)" to be able to naviagate easily into each page as per reqirement
			2) We Create a "Pie Chart" to show the Quarter wise max values of "Carbon Monoxide(CO),"Ozone(O3)","Sulphur Dioxide (SO2) AND "Nitrogen Dioxide (NO2)"
			3) We also add the Map to mark the cities of US  and a Table to display the County and the County Code
			4) Lastly we  add  separate slicers  for " Date" , "Country" ,"State" "City" to the page to be able to filter the Visuals on the basis of each of them .

- Step 6 : Next we create the report for  Carbon Monoxide(CO)
			1)"4 Cards" where in we visualize the 1st Max Hour , 1st Max value(IN Parts per Million) , City with Highest CO AQI & the Unit of CO 
			2)Next We create  a "horizontal stacked bar chart" to  visualize the Top 10 Sates with Highest CO AQI . Also we Create a "Table" to  Mark the Highest CO AQI with respect to state code .
			3)Next another "Table" is created to Display the Top state with the value of CO AQI.
			4)We plot an "Area chart" to display the max value of CO AQi over the Years.
			5)We also create a "date slicer" to filter the fields on the basis of date 
			6)In the end we create a "Arrow Shape" to navigate back to the Overview Page.

- Step 7 : Next we create the report for  Ozone (O3)
			1)"4 Cards" where in we visualize the 1st Max Hour O3 , 1st Max value(IN Parts per Million) O3 , City with Highest O3 AQI & the Units of O3 
			2)Next We create  a "horizontal stacked bar chart" to  visualize the Top 10 Sates with Highest O3 AQI . Also we Create a "Table" to  Mark the Highest O3 AQI with respect to state code .
			3)Next another "Table" is created to Display the Top state with the value of O3 AQI.
			4)We plot an "Area chart" to display the max value of O3 AQi over the Years.
			5)We also create a "date slicer" to filter the fields on the basis of date 
			6)In the end we create a "Arrow Shape" to navigate back to the Overview Page.

- Step 8: Next we create the report for  Sulphur Dioxide(SO2)
			1)"4 Cards" where in we visualize the 1st Max Hour SO2 , 1st Max value(IN Parts per Billion) SO2, City with Highest SO2 AQI & the Units of SO2
			2)Next We create  a "horizontal stacked bar chart" to  visualize the Top 10 Sates with Highest SO2 AQI . Also we Create a "Table" to  Mark the Highest SO2 AQI with respect to state code .
			3)Next another "Table" is created to Display the Top state with the value of SO2 AQI.
			4)We plot an "Area chart" to display the max value of SO2 AQi over the Years.
			5)We also create a "date slicer" to filter the fields on the basis of date 
			6)In the end we create a "Arrow Shape" to navigate back to the Overview Page.


- Step 9: Next we create the report for  Nitrogen Dioxide(NO2)
			1)"4 Cards" where in we visualize the 1st Max Hour NO2 , 1st Max value(IN Parts per Billion) NO2, City with Highest NO2 AQI & the Units of NO2
			2)Next We create  a "horizontal stacked bar chart" to  visualize the Top 10 Sates with Highest NO2 AQI . Also we Create a "Table" to  Mark the Highest NO2 AQI with respect to state code .
			3)Next another "Table" is created to Display the Top state with the value of NO2 AQI.
			4)We plot an "Area chart" to display the max value of NO2 AQi over the Years.
			5)We also create a "date slicer" to filter the fields on the basis of date 
			6)In the end we create a "Arrow Shape" to navigate back to the Overview Page.


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

--The date range for the below mwntioned report is from the period of 1st Jan 2016 to 31st Dec 2010


1) 1st Max Value of  Carbon Monoxide (CO) is 16.50 units in parts per million
2) City With Highest  Carbon Monoxide (CO) AQI  is Mexicali , State - Country Of Mexico With a Max AQI of  150
3) Top 10 States with Max Carbon Monoxide (C0) presence in AQI  is Country of Mexico,California,Texas,New Hampshire, District of Columbia,Arizona,Colorado,Louisiana,Pennsylvania,Illinois
4) There Has been significant reduction in Carbon Monoxide (CO) AQI  from the year 2006( AQI-150) TO 2010 ( AQI-51)

5) 1st Max Value of  Ozone(O3) is 0.14 units in parts per million
6) City With Highest  Ozone(O3) AQI  is Mexicali , State - Country Of Mexico With a Max AQI of  211
7) Top 10 States with Max Ozone(O3) presence in AQI  is Country of Mexico,California,North Carolina,Pennsylvania, Texas,Virginia,New York, Maryland,Missouri,Connecticut
8) The trend for Ozone O3 AQI has remained more or less in consant side  from the year 2006( AQI-206) TO 2010 ( AQI-200) except for the only marginal increse seen in the year 2007

9) 1st Max Value of  Sulphur Dioxide(SO2) is 351 units in parts per Billion
10) City With Highest  Sulphur Dioxide(SO2) AQI  is Park Hill , State - Oklahoma with a Max AQI of  200
11) Top 10 States with Max Sulphur Dioxide(SO2) presence in AQI  is OklaHoma , Colorado, California,Pennsylvania,Maryland,Country of Mexico, North Carolina, Texas,New Hampshire, Ohio
12) There Has been significant reduction in Sulphur Dioxide(SO2) AQI  from the year 2006( AQI-200) TO 2010 ( AQI-103)

13) 1st Max Value of Nitrogen Dioxide(NO2) is 176 units in parts per Billion
14) City With Highest  Nitrogen Dioxide(NO2) AQI  is Tijuana , State - Country of Mexico with a Max AQI of  115
15) Top 10 States with Max Nitrogen Dioxide(NO2) presence in AQI  is Country of Mexico, Colorado,Louisiana,District of Columbia,Texas,New York,Pennsylvania,Connecticut
16) The Nitrogen Dioxide(NO2) AQI has decreased from the year 2006( AQI-200) TO 2010 ( AQI-103)

#Dashboard Snaps(Power BI Service)
![Snap1](https://github.com/bigit91/port1/assets/155818756/b9a73d50-38b4-4e5c-8f1f-fb7336cb9a40)

![Snap2](https://github.com/bigit91/port1/assets/155818756/e14589e4-0d8a-4b02-a0e9-5eaf5d95051b)

![Snap3](https://github.com/bigit91/port1/assets/155818756/595b6189-d810-4800-af2d-726cfb6ff0cf)

![Snap4](https://github.com/bigit91/port1/assets/155818756/483e3087-b20f-4491-9435-557ea5b323d7)

![Snap5](https://github.com/bigit91/port1/assets/155818756/690c7d23-901d-48cb-b820-3c82b4a4d3ef)








