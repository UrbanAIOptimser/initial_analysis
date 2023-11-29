# initial_analysis

## API
### Open Data Barcelona
https://opendata-ajuntament.barcelona.cat/en

### Google Maps API:
https://developers.google.com/maps/documentation/javascript/overview
https://developers.google.com/maps/documentation/places/web-service/overview
https://developers.google.com/maps/documentation/geocoding/overview
https://developers.google.com/maps/documentation/directions/overview
https://developers.google.com/maps/documentation/distance-matrix/overview
https://developers.google.com/maps/documentation/streetview/overview


### TMB (Transports Metropolitans de Barcelona) API: Offers access to public transportation data, including schedules, routes, and real-time updates for buses, metro, and trams.
https://www.tmb.cat/en/home
OpenStreetMap: Open-source map data that can be used to develop custom maps for the app.
Overpass API: This is a read-only API that allows to query OSM data using a specialised query language. It enables to fetch map data based on criteria like geographical area, types of features, tags, etc.
osmAPI: OSM also provides a RESTful API that allows basic editing capabilities. This can be used to retrieve map data within bounding boxes, create and update map features, and more. However, its editing capabilities are limited compared to Overpass.
### Weather APIs: Access to weather forecasts and conditions can help users plan their activities.
https://openweathermap.org/api

### Local News Outlets: Some news outlets offer APIs for accessing local news articles and updates.
https://www.eventbrite.com/
https://www.meetup.com/

### Social Media APIs: Platforms like Facebook or Instagram might offer location-based data for events and community happenings.
https://developer.twitter.com/en
https://developers.facebook.com/docs/instagram-basic-display-api
https://developers.facebook.com/docs/graph-api

### Tourism APIs:
https://www.barcelonaturisme.com/wv3/en/

### Data from AirQuality Measurement StationsBarcelona
 https://opendata-ajuntament.barcelona.cat/data/es/dataset/qualitat-aire-detall-bcn
 

### Vehicles cAccidentsUrbanPoliceBarcelona
https://opendata-ajuntament.barcelona.cat/data/es/dataset/accidents-vehicles-gu-bcn

### IncidentsUrbanPoliceBarcelona
https://opendata-ajuntament.barcelona.cat/data/es/dataset/accidents-gu-bcn)  


## Dataset - (hardcopy)

### Chicago Divvy Bicycle Sharing Data (202004-divvy-tripdata)
https://www.kaggle.com/datasets/yingwurenjian/chicago-divvy-bicycle-sharing-data/data
Sharing bicycles represent a healthier and environment-friendly lifestyle. There could be some interesting mechanism behind the sharing bicycles.

Content
In this project, the data comes from Chicago Divvy bicycle sharing system as well as the weather information in Chicago.

Divvy Data: https://www.divvybikes.com/system-data

Weather Data: https://www.wunderground.com/

I download the bicycle data from Divvy website from 2013 to 2017. In addition, I also queried the weather information for Chicago from https://www.wunderground.com/.

data_raw.csv: contains all the bicycle data from 2013 to 2017, it also contains all the weather information. There are a lot of values missing

data.csv: contains the data that has been cleaned. I deleted some useless weather information and keep the trips that are within 1 hour. Also, I delete some data with missing values.

### Traveler Trip Dataset (Travel details dataset)
https://www.kaggle.com/datasets/rkiattisak/traveler-trip-data
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
https://www.kaggle.com/datasets/teamincribo/greece-travel-data?select=README.md
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
https://www.kaggle.com/datasets/ddosad/customer-behaviour-tourism-portal
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
https://www.kaggle.com/datasets/bluehorseshoe/uk-2016-road-safety-data?select=Road-Accident-Safety-Data-Guide.xls
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
https://www.kaggle.com/datasets/offerl/bus-trip-data-august-16-to-august-20-2022?select=bus_trip1_data_2022-08-16_to_2022-08-20.csv
This dataset contains Real-Time Transit Data (RTTD) for a selection of bus trips from August 16 to August 20, 2022. The data can provide insights into the operational details of bus journeys within the specified time frame.
The purpose of this dataset is to facilitate research, analysis, and exploration of bus operations and travel patterns during the specified period. Data analysts, researchers, and transit enthusiasts can utilize this dataset to gain insights into bus service performance, identify patterns in bus scheduling, and study travel behavior.

### Bike Share Data
https://www.kaggle.com/datasets/shaltout/explore-bike-share-data?select=washington.csv
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
https://www.kaggle.com/datasets/mysarahmadbhat/nyc-traffic-accidents?select=NYC+Accidents+2020.csv
Motor vehicle collisions reported by the New York City Police Department from January-August 2020. Each record represents an individual collision, including the date, time and location of the accident (borough, zip code, street name, latitude/longitude), vehicles and victims involved, and contributing factors.

Recommended Analysis
Compare the % of total accidents by month. Do you notice any seasonal patterns?
Break down accident frequency by day of week and hour of day. Based on this data, when do accidents occur most frequently?
On which particular street were the most accidents reported? What does that represent as a % of all reported accidents?
What was the most common contributing factor for the accidents reported in this sample (based on Vehicle 1)? What about for fatal accidents specifically?


### Transportation Dataset
https://www.kaggle.com/datasets/amitzala/transportation-dataset?select=transportation-to-work-1.xlsx
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



### Pollution_Random
https://www.kaggle.com/datasets/srilaasyakandukuri/pollution-random
This dataset is generated by ChatGPT using Random Package
Pollution prediction is a valuable application in environmental science and public health. It aims to forecast the levels of various pollutants in the air, water, or soil at specific locations and time intervals. The primary uses and benefits of pollution prediction include:

Environmental Monitoring: Pollution prediction helps monitor and assess the current and future levels of pollutants in the environment. It enables authorities and researchers to understand the extent of pollution, identify hotspots, and track pollution trends over time.

Health Risk Assessment: Predicting pollution levels can provide insights into the potential health risks associated with exposure to pollutants. By understanding the anticipated pollution levels, authorities can issue health advisories and take preventive measures to protect vulnerable populations.

Urban Planning and Policy Making: Pollution prediction models contribute to urban planning efforts by considering the potential environmental impacts of infrastructure projects, land use changes, and transportation systems. This information helps policymakers make informed decisions to minimize pollution and promote sustainable development.

Emergency Response and Preparedness: During events such as industrial accidents, wildfires, or natural disasters, pollution prediction can assist in emergency response planning. By forecasting pollutant dispersion patterns, authorities can take appropriate measures to evacuate affected areas, protect public health, and mitigate the immediate and long-term environmental consequences.

Air Quality Management: Pollution prediction is crucial for air quality management programs. It aids in the identification of pollution sources, evaluation of emission reduction strategies, and the design of effective control measures to improve air quality and comply with regulatory standards.


### Air Quality in Biggest Cities of the World
https://www.kaggle.com/datasets/timmofeyy/air-quality-in-biggest-cities-of-the-world?select=world_air_quality_with_locations.csv
Pollutant from Dataset
PM2.5 (Particulate Matter 2.5 micrometers or smaller): PM2.5 refers to fine particles suspended in the air with a diameter of 2.5 micrometers or smaller. These particles can come from various sources such as vehicle emissions, industrial processes, and natural sources like dust and pollen. PM2.5 particles can penetrate deep into the respiratory system and have adverse effects on human health.

O3 (Ozone): Ground-level ozone is a reactive gas formed when sunlight reacts with pollutants like volatile organic compounds (VOCs) and nitrogen oxides (NOx). It is a major component of smog and can cause respiratory problems, especially in sensitive individuals like children, the elderly, and people with respiratory conditions.

NO2 (Nitrogen Dioxide): Nitrogen dioxide is a reddish-brown gas primarily emitted from vehicle exhaust and combustion processes in industries and power plants. It can irritate the respiratory system and contribute to the formation of smog and acid rain.

PM10 (Particulate Matter 10 micrometers or smaller): PM10 refers to larger particles with a diameter of 10 micrometers or smaller. These particles include both fine and coarse particles, originating from sources like construction activities, road dust, and industrial processes. While they are not as fine as PM2.5, they can still have health impacts when inhaled.

SO2 (Sulfur Dioxide): Sulfur dioxide is a gas produced by burning fossil fuels, especially those containing sulfur, like coal and oil. It can lead to respiratory issues and contribute to the formation of acid rain, which can have detrimental effects on the environment and human-made structures.

These pollutants are often monitored as part of air quality assessments to ensure public health and environmental protection. Regulatory agencies and organizations establish air quality standards and guidelines to limit the concentration of these pollutants in the atmosphere to reduce their negative impacts.

Source names from Dataset:
ChinaAQIData: ChinaAQIData refers to the Air Quality Index (AQI) used in China to assess and communicate the level of air pollution. It takes into account various pollutants like PM2.5, PM10, sulfur dioxide (SO2), nitrogen dioxide (NO2), ozone (O3), and carbon monoxide (CO). The AQI is typically divided into different categories (e.g., Good, Moderate, Unhealthy) to inform the public about air quality conditions and associated health risks.

AirNow: AirNow is a United States government-operated platform that provides real-time and forecasted air quality information to the public. It offers an AQI calculation based on various pollutants and includes color-coded categories to help people understand air quality conditions in their area.

caaqm (Centralized Air Quality Monitoring): Caaqm refers to the centralized air quality monitoring system used in various regions to monitor air pollution levels. This system typically involves a network of monitoring stations that measure pollutants and report data to regulatory agencies. It helps in assessing compliance with air quality standards and making informed policy decisions.

EEA Spain: EEA stands for the European Environment Agency. EEA Spain refers to the air quality monitoring and reporting activities specific to Spain under the umbrella of the European Union. The EEA compiles air quality data from various European countries to assess air quality trends and inform policies aimed at improving air quality and reducing pollution.

EEA Germany: Similarly, EEA Germany refers to the air quality monitoring and reporting activities specific to Germany within the European Union. It involves data collection, analysis, and reporting on air quality conditions in Germany to contribute to the overall understanding of air pollution in Europe.

These platforms and systems play a crucial role in informing the public, policymakers, and researchers about air quality conditions and trends, promoting awareness and action to address air pollution and its impacts.

About Units in Dataset:
µg/m³ and ppm are units of measurement commonly used to express concentrations of substances in the air. They are often used to quantify the amount of pollutants or gases present in the atmosphere. Here's what each unit means:

µg/m³ (micrograms per cubic meter):
This unit measures the concentration of a substance in the air by indicating the mass of that substance per unit volume of air. It is used to express the amount of particulate matter or solid particles suspended in the air. Micrograms (µg) are a unit of mass, and cubic meters (m³) are a unit of volume. So, when you see a value like "10 µg/m³," it means there are 10 micrograms of the substance in every cubic meter of air.

ppm (parts per million):
PPM is a unit used to express the concentration of a substance in a gaseous mixture. It indicates the number of parts of a particular substance per one million parts of the total mixture by volume. This unit is often used for gases such as pollutants, gases in the atmosphere, or trace elements. For example, if the concentration of a gas is 1 ppm, it means that there is one part of that gas for every one million parts of the mixture.

Both units are essential for assessing air quality and environmental monitoring, especially in areas where the presence of pollutants or gases can have health or ecological impacts. Different substances might have different recommended exposure limits in these units to ensure human and environmental safety.


### 🏖️🌊Beach weather stations🏖️🌊
https://www.kaggle.com/datasets/sanjanchaudhari/beach-weather-stations?select=Beach_Weather_Stations_-_Automated_Sensors.csv
Beach weather stations serve several important purposes. Firstly, they provide valuable information to individuals planning a visit to the beach. By accessing the weather data provided by these stations, beachgoers can make informed decisions about what activities to engage in, what clothing to wear, and how to protect themselves from potential weather hazards.

Beach weather stations also aid in long-term weather monitoring and analysis. The collected data helps researchers, climatologists, and environmentalists study coastal weather patterns, monitor climate change impacts, and analyze trends specific to beach areas. This information is valuable for understanding the dynamics of coastal ecosystems and supporting conservation efforts.

Beach weather stations dataset is including a this column: Station Name, Measurement Timestamp, Air Temperature, Wet Bulb Temperature, Humidity, Rain Intensity, Interval Rain, Total Rain, Precipitation Type, Wind Direction, Wind Speed, Maximum Wind Speed, Barometric Pressure, Solar Radiation, Heading, Battery Life, Measurement Timestamp Label, Measurement ID.

I explain each column one by one :-

Station Name: The name or identifier of the weather station where the measurements were recorded. This helps identify the specific location or source of the weather data.

Measurement Timestamp: The date and time at which the weather measurements were taken. It indicates the exact moment when the weather variables were recorded.

Air Temperature: The temperature of the air at the time of measurement, typically recorded in degrees Celsius or Fahrenheit. It represents the level of warmth or coolness of the surrounding air.

Wet Bulb Temperature: The temperature recorded by a thermometer with a wet bulb, which indicates the lowest temperature that can be reached through evaporative cooling. It provides insights into humidity and atmospheric conditions.

Humidity: The amount of moisture present in the air, usually expressed as a percentage. It indicates the level of water vapor saturation in the atmosphere.

Rain Intensity: The rate at which rainfall occurs during a specific time period, typically measured in millimeters per hour. It represents the intensity or heaviness of rain.

Interval Rain: The amount of rain that has fallen during a specific interval of time, usually measured in millimeters. It provides information about the cumulative rainfall over a given period.

Total Rain: The total amount of rainfall recorded over a specified duration, typically measured in millimeters. It represents the cumulative precipitation during a specific time frame.

Precipitation Type: Describes the type of precipitation observed, such as rain, snow, sleet, or hail. It indicates the form in which the water is falling from the atmosphere.

Wind Direction: The compass direction from which the wind is blowing, expressed in degrees or cardinal directions (e.g., north, south, east, west). It provides information about the wind's source and movement.

Wind Speed: The speed of the wind, usually measured in units like meters per second or miles per hour. It indicates the rate at which the air is moving horizontally.

Maximum Wind Speed: The highest wind speed recorded during a specific time period. It represents the peak intensity of the wind during that time frame.

Barometric Pressure: The atmospheric pressure exerted by the Earth's atmosphere, typically measured in units like millibars or inches of mercury. It provides insights into weather patterns and atmospheric conditions.

Solar Radiation: The amount of radiant energy received from the sun, usually measured in watts per square meter. It represents the intensity of solar energy reaching the Earth's surface.

Heading: Refers to the direction or orientation of a specific instrument or sensor. It is often used in relation to wind direction or other directional measurements.

Battery Life: Indicates the remaining capacity or level of charge in the battery of the weather station or measurement device. It helps ensure the reliability of the recorded data.

Measurement Timestamp Label: A descriptive label or text associated with the measurement timestamp, providing additional information or context about the measurement point.

Measurement ID: An identifier or unique reference assigned to each individual measurement or data point. It helps track and organize the collected data.

These variables collectively provide a comprehensive picture of weather conditions at a specific location and time. By analyzing and interpreting these measurements, researchers and meteorologists can gain insights into weather patterns, climate trends, and environmental conditions.


### Air Pollution and Mental Health
https://www.kaggle.com/datasets/thedevastator/air-pollution-and-mental-health?select=CitieSHealth_BCN_DATA_PanelStudy_20220414.csv
Identifying Short-Term Human Impacts of Air Pollution
By [[https://zenodo.org/records/6503022#.Y8OrG9JBwUE]]

About this dataset
This dataset from the CitieS-Health project provides a unique insight into the impact of air pollution on humans. It is comprised of data collected in Barcelona, Spain, and examines various environmental variables, such as air pollution levels, and their effects on mental health and wellbeing. In addition to environmental factors, this dataset also captures self-reported survey data on mental health, physical activity, diet habits, and more. From performance in a Stroop test to information on total noise exposure at 55 dB - this comprehensive dataset will give you everything you need to understand the link between air pollution and human health so that we can begin finding better solutions for a cleaner future

More Datasets
For more datasets, click here.

Featured Notebooks
🚨 Your notebook can be here! 🚨!
How to use the dataset
This dataset captures information on air pollution levels and variables related to mental health, such as performance in a Stroop test and self-reported surveys on mental health, physical activity, diet, and other factors. It can be used to answer the question “how does short-term exposure to air pollution affect human mental health?”

To use this dataset, start by understanding the variables you are interested in exploring. Look for correlations between environmental conditions (i.e., air pollution levels) and measures of wellbeing (i.e., performance in a Stroop test). Additionally pay special attention to any factors that may be associated with different levels of exposure (like access to green/blue spaces within 300m buffer).

Next you should examine any relevant self-reported surveys questions related to mental health or wellbeing (such as bienestar or sueno). For example consider looking at how responses vary based on age or gender; it is possible that some demographic groups are more sensitive than others when exposed to air pollutants.
Finally consider incorporating information from other external sources like local noise levels or traffic patterns into your analysis – these will help contextualise your findings even further.

Using this dataset you can begin uncovering the impact of short-term exposure to air pollution on humans – by combining different variables together understanding what correlations exist between environment conditions and measures of wellbeing can help people make better decisions about their lifestyle choices like where they choose live, work or play!

Research Ideas
Analyzing the differences in response time in Stroop tests by age and gender. By looking at the accurate response time when it comes to completing a Stroop test from participants of different genders and ages, conclusions can be drawn about how our responses are affected by environmental factors like air pollution levels and noise exposure

Correlating green-space access with mental health outcomes over a period of time. This dataset can be used to analyze if access to green spaces has an impact on overall mental wellbeing indices like stress levels or perceived mood over a certain study period - allowing us to inform policies that leverage locations of urban green-spaces for better outcomes especially in heavily polluted cities

Acknowledgements
