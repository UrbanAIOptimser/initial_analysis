# User Profiling und Behaviour Anslysis

## Data collecting and Processing: user Interactions of the data.
  * User Interactions: Clicks, searches, bookings, and browsing history on travel platforms.

## Machine Learning model based on their preferentes and behaviours such as travel habits.
  * Preferences: Explicit user inputs on destinations, budget, accommodation, and activities.
  * Behavioral Data: Frequency of travel, seasonality, preferred travel modes, duration of stays, etc.
## Recommendation algorithms (Collaborative filtering or content-based) to suggest travel options based on User Preferenses and historical data.
  * Past travel patterns, destinations visited, ratings, and reviews.


## Dataset
  * Chicago Divvy Bicycle Sharing Data (202004-divvy-tripdata)
Sharing bicycles represent a healthier and environment-friendly lifestyle. There could be some interesting mechanism behind the sharing bicycles.

Content
In this project, the data comes from Chicago Divvy bicycle sharing system as well as the weather information in Chicago.

Divvy Data: https://www.divvybikes.com/system-data

Weather Data: https://www.wunderground.com/

I download the bicycle data from Divvy website from 2013 to 2017. In addition, I also queried the weather information for Chicago from https://www.wunderground.com/.

data_raw.csv: contains all the bicycle data from 2013 to 2017, it also contains all the weather information. There are a lot of values missing

data.csv: contains the data that has been cleaned. I deleted some useless weather information and keep the trips that are within 1 hour. Also, I delete some data with missing values.

* Traveler Trip Dataset (Travel details dataset)
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


* Greece Travel Data (travel_tourism_dataset)

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



* Tourism Page Engagement (Customer behaviour Tourism)
This dataset provides complete information about Customer behaviour for a typical Social Media page of tourism company.

Variable and Description
UserID: Unique ID of the user
Buy_ticket:	Buy a ticket in the next month (target variable)
Yearly_avg_view_on_travel_page:	Average yearly views on any travel-related page by the user
preferred_device	Preferred device for user login
total_likes_on_outstation_checkin_given:	Total number of likes given by the user on out-of-station check-ins in the last year
yearly_avg_Outstation_checkins:	Average number of out-of-station check-ins done by the user
member_in_family:	Total number of relationships mentioned by the user in the account
preferred_location_type:	Preferred type of location for traveling by the user
Yearly_avg_comment_on_travel_page:	Average yearly comments on any travel-related page by the user
total_likes_on_outofstation_checkin_received:	Total number of likes received by the user on out-of-station check-ins in the last year
week_since_last_outstation_checkin:	Number of weeks since the last out-of-station check-in update by the user
following_company_page:	Whether the customer is following the company page (Yes or No)
montly_avg_comment_on_company_page:	Average monthly comments on the company page by the user
working_flag:	Whether the customer is working or not
travelling_network_rating:	The rating indicating if the user has close friends who also like traveling. 1 is high, 4 is lowest
Adult_flag:	Whether the customer is an adult or not
Daily_Avg_mins_spend_on_traveling_page:	Average time spent on the company's travel page by the user
