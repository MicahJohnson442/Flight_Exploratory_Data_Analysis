According to the Federal Aviation Administration (FAA), their Air Traffic Organization (ATO) provides service to more than 45,000 flights every day. As of 2020, there were 59 airlines in the United States, 18 of which are classified as major carriers with over $1 billion in revenue. The airlines in the U.S. can be divided into three main categories: full-service legacy carriers, low-cost carriers and regional carriers.  

In this project, I will carry out an Exploratory Data Analysis on a dataset from the US Department of Transportation. The following questions were answered through the analysis of the data: 

What are the average (mean) departure and arrival delays? 

How do the carriers compare in terms of arrival delay performance? 

Is there a noticeable difference in arrival delays for different days of the week? 

Which departure airport has the highest average departure delay? 

Do late departures tend to result in longer arrival delays than on-time departures? 

Which route (from origin airport to destination airport) has the most late arrivals? 

Which route has the highest average arrival delay? 

 

## The dataset contains observations of US domestic flights in 2013, and consists of the following fields: 

Year: The year of the flight (all records are from 2013) 

Month: The month of the flight 

DayofMonth: The day of the month on which the flight departed 

DayOfWeek: The day of the week on which the flight departed - from 1 (Monday) to 7 (Sunday) 

Carrier: The two-letter abbreviation for the airline. 

OriginAirportID: A unique numeric identifier for the departure aiport 

OriginAirportName: The full name of the departure airport 

OriginCity: The departure airport city 

OriginState: The departure airport state 

DestAirportID: A unique numeric identifier for the destination aiport 

DestAirportName: The full name of the destination airport 

DestCity: The destination airport city 

DestState: The destination airport state 

CRSDepTime: The scheduled departure time 

DepDelay: The number of minutes departure was delayed (flight that left ahead of schedule have a negative value) 

DelDelay15: A binary indicator that departure was delayed by more than 15 minutes (and therefore considered "late") 

CRSArrTime: The scheduled arrival time 

ArrDelay: The number of minutes arrival was delayed (flight that arrived ahead of schedule have a negative value) 

ArrDelay15: A binary indicator that arrival was delayed by more than 15 minutes (and therefore considered "late") 

Cancelled: A binary indicator that the flight was cancelled 
