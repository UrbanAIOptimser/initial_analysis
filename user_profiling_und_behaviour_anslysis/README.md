# User Profiling und Behaviour Anslysis

## Data collecting and Processing: user Interactions of the data.
  * User Interactions: Clicks, searches, bookings, and browsing history on travel platforms.

## Machine Learning model based on their preferentes and behaviours such as travel habits.
  * Preferences: Explicit user inputs on destinations, budget, accommodation, and activities.
  * Behavioral Data: Frequency of travel, seasonality, preferred travel modes, duration of stays, etc.
## Recommendation algorithms (Collaborative filtering or content-based) to suggest travel options based on User Preferenses and historical data.
  * Past travel patterns, destinations visited, ratings, and reviews.


## Dataset
### Chicago Divvy Bicycle Sharing Data (202004-divvy-tripdata)
Sharing bicycles represent a healthier and environment-friendly lifestyle. There could be some interesting mechanism behind the sharing bicycles.

Content
In this project, the data comes from Chicago Divvy bicycle sharing system as well as the weather information in Chicago.

Divvy Data: https://www.divvybikes.com/system-data

Weather Data: https://www.wunderground.com/

I download the bicycle data from Divvy website from 2013 to 2017. In addition, I also queried the weather information for Chicago from https://www.wunderground.com/.

data_raw.csv: contains all the bicycle data from 2013 to 2017, it also contains all the weather information. There are a lot of values missing

data.csv: contains the data that has been cleaned. I deleted some useless weather information and keep the trips that are within 1 hour. Also, I delete some data with missing values.

### Traveler Trip Dataset (Travel details dataset)
The travel dataset provides detailed information on various trips taken by travelers, including their destination, travel dates, duration of the trip in days, traveler demographics (name, age, gender, and nationality), as well as the type and cost of accommodation and transportation. This dataset can be used to gain insights into travel patterns, preferences, and behaviors of different types of travelers. It can also be helpful for travel-related businesses, such as travel agencies, to create tailored marketing strategies and travel packages that meet the needs and preferences of different travelers.

Column details:

• Trip ID: A unique identifier for each trip taken by a traveler.

• Destination: The name of the city or country visited by the traveler.

• Start date: The date the traveler started the trip.

• End date: The date the traveler ended the trip.

• Duration (days): The number of days the traveler spent on the trip.

• Traveler name: The name of the traveler.

• Traveler age: The age of the traveler at the time of the trip.

• Traveler gender: The gender of the traveler.

• Traveler nationality: The nationality of the traveler.

• Accommodation type: The type of accommodation the traveler stayed in, such as hotel, hostel, or Airbnb.

• Accommodation cost: The cost of the accommodation for the entire trip.

• Transportation type: The mode of transportation used by the traveler, such as plane, train, or car.

• Transportation cost: The cost of transportation for the entire trip.


### Greece Travel Data (travel_tourism_dataset)

Synthetically generated dataset of travel history(Greece)
Contains:
10,000 record details,
14 column metrics,
Travel History,
Diverse variations,
A mix of real and synthetic data.

Metrics include:
Trip #no.
Location(Greece)
Duration
Cost of Travel(Entire Trip)
Mode of Travel
Stay
First Name
Last Name
Date of Birth
Address
Age
Sex
Nationality
Date of Traveler

### Tourism Page Engagement (Customer behaviour Tourism)
This dataset provides complete information about Customer behaviour for a typical Social Media page of tourism company.

Variable and Description
* UserID: Unique ID of the user
* Buy_ticket:	Buy a ticket in the next month (target variable)
* Yearly_avg_view_on_travel_page:	Average yearly views on any travel-related page by the user
* preferred_device:	Preferred device for user login
* total_likes_on_outstation_checkin_given:	Total number of likes given by the user on out-of-station check-ins in the last year
* yearly_avg_Outstation_checkins:	Average number of out-of-station check-ins done by the user
* member_in_family:	Total number of relationships mentioned by the user in the account
* preferred_location_type:	Preferred type of location for traveling by the user
* Yearly_avg_comment_on_travel_page:	Average yearly comments on any travel-related page by the user
* total_likes_on_outofstation_checkin_received:	Total number of likes received by the user on out-of-station check-ins in the last year
* week_since_last_outstation_checkin:	Number of weeks since the last out-of-station check-in update by the user
* following_company_page:	Whether the customer is following the company page (Yes or No)
* montly_avg_comment_on_company_page:	Average monthly comments on the company page by the user
* working_flag:	Whether the customer is working or not
* travelling_network_rating:	The rating indicating if the user has close friends who also like traveling. 1 is high, 4 is lowest
* Adult_flag:	Whether the customer is an adult or not
* Daily_Avg_mins_spend_on_traveling_page:	Average time spent on the company's travel page by the user

### UK 2016 Road Safety Data

UK police forces collect data on every vehicle collision in the UK on a form called Stats19. Data from this form ends up at the DfT and is published at https://data.gov.uk/dataset/road-accidents-safety-data

Content
There are 4 CSVs and an Excel file in this set. Accidents is the primary table and has references by Accident_Index to the other tables.

Acknowledgements
Department for Transport and the UK's wonderful Open Gov initiative https://data.gov.uk/

Inspiration
Are there patterns for accidents involving different road users?
Can we predict the safest / most dangerous times to travel
Can this data help route cyclists around accident hotspots taking into account the time of day, weather, route etc
Are certain cars more accident prone than others?



### Real-Time Bus Journeys: Exploring Transit Data

This dataset contains Real-Time Transit Data (RTTD) for a selection of bus trips from August 16 to August 20, 2022. The data can provide insights into the operational details of bus journeys within the specified time frame.
The purpose of this dataset is to facilitate research, analysis, and exploration of bus operations and travel patterns during the specified period. Data analysts, researchers, and transit enthusiasts can utilize this dataset to gain insights into bus service performance, identify patterns in bus scheduling, and study travel behavior.

### Bike Share Data
Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.

Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

In this project, you will use data provided by Motivate, a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. You will compare the system usage between three large cities: Chicago, New York City, and Washington, DC.

The Datasets
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

Start Time (e.g., 2017-01-01 00:07:57)
End Time (e.g., 2017-01-01 00:20:53)
Trip Duration (in seconds - e.g., 776)
Start Station (e.g., Broadway & Barry Ave)
End Station (e.g., Sedgwick St & North Ave)
User Type (Subscriber or Customer)
The Chicago and New York City files also have the following two columns:

Gender
Birth Year

Data for the first 10 rides in the new_york_city.csv file

The original files are much larger and messier, and you don't need to download them, but they can be accessed here if you'd like to see them (Chicago, New York City, Washington). These files had more columns and they differed in format in many cases. Some data wrangling has been performed to condense these files to the above core six columns to make your analysis and the evaluation of your Python skills more straightforward. In the Data Wrangling course that comes later in the Data Analyst Nanodegree program, students learn how to wrangle the dirtiest, messiest datasets, so don't worry, you won't miss out on learning this important skill!

Statistics Computed
You will learn about bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. In this project, you'll write code to provide the following information:

1 Popular times of travel (i.e., occurs most often in the start time)
most common month
most common day of week
most common hour of day

2 Popular stations and trip
most common start station
most common end station
most common trip from start to end (i.e., most frequent combination of start station and end station)

3 Trip duration
total travel time
average travel time

4 User info
counts of each user type
counts of each gender (only available for NYC and Chicago)
earliest, most recent, most common year of birth (only available for NYC and Chicago)
The Files
To answer these questions using Python, you will need to write a Python script. To help guide your work in this project, a template with helper code and comments is provided in a bikeshare.py file, and you will do your scripting in there also. You will need the three city dataset files too:

chicago.csv
new_york_city.csv
washington.csv

All four of these files are zipped up in the Bikeshare file in the resource tab in the sidebar on the left side of this page. You may download and open up that zip file to do your project work on your local machine.


### NYC Traffic Accidents
Motor vehicle collisions reported by the New York City Police Department from January-August 2020. Each record represents an individual collision, including the date, time and location of the accident (borough, zip code, street name, latitude/longitude), vehicles and victims involved, and contributing factors.

Recommended Analysis
Compare the % of total accidents by month. Do you notice any seasonal patterns?
Break down accident frequency by day of week and hour of day. Based on this data, when do accidents occur most frequently?
On which particular street were the most accidents reported? What does that represent as a % of all reported accidents?
What was the most common contributing factor for the accidents reported in this sample (based on Vehicle 1)? What about for fatal accidents specifically?


### Transportation Dataset

DESCRIPTION
This table contains data on the percent of residents aged 16 years and older mode of transportation to work for …

SUMMARY
This table contains data on the percent of residents aged 16 years and older mode of transportation to work for California, its regions, counties, cities/towns, and census tracts. Data is from the U.S. Census Bureau, Decennial Census and American Community Survey. The table is part of a series of indicators in the Healthy Communities Data and Indicators Project of the Office of Health Equity. Commute trips to work represent 19% of travel miles in the United States. The predominant mode – the automobile - offers extraordinary personal mobility and independence, but it is also associated with health hazards, such as air pollution, motor vehicle crashes, pedestrian injuries and fatalities, and sedentary lifestyles. Automobile commuting has been linked to stress-related health problems. Active modes of transport – bicycling and walking alone and in combination with public transit – offer opportunities for physical activity, which is associated with lowering rates of heart disease and stroke, diabetes, colon and breast cancer, dementia and depression. Risk of injury and death in collisions are higher in urban areas with more concentrated vehicle and pedestrian activity. Bus and rail passengers have a lower risk of injury in collisions than motorcyclists, pedestrians, and bicyclists. Minority communities bear a disproportionate share of pedestrian-car fatalities; Native American male pedestrians experience four times the death rate Whites or Asian pedestrians, and African-Americans and Latinos experience twice the rate as Whites or Asians. More information about the data table and a data dictionary can be found in the About/Attachments section.

* ind_id - Indicator ID
* ind_definition - Definition of indicator in plain language
* reportyear - Year that the indicator was reported
* race_eth_code - numeric code for a race/ethnicity group
* race_eth_name - Name of race/ethnic group
* geotype - Type of geographic unit
* geotypevalue - Value of geographic unit
* geoname - Name of a geographic unit
* county_name - Name of county that geotype is in
* county_fips - FIPS code of the county that geotype is in
* region_name - MPO-based region name; see MPO_County list tab
* region_code - MPO-based region code; see MPO_County list tab
* mode - Mode of transportation short name
* mode_name - Mode of transportation long name
* pop_total - denominator
* pop_mode - numerator
*percent - Percent of Residents Mode of Transportation to Work,
* Population Aged 16 Years and Older
* LL_95CI_percent - The lower limit of 95% confidence interval
* UL_95CI_percent - The lower limit of 95% confidence interval
* percent_se - Standard error of the percent mode of transportation
* percent_rse - Relative standard error (se/value) expressed as a percent
* CA_decile - California decile
* CA_RR - Rate ratio to California rate
* version - Date/time stamp of a version of data
