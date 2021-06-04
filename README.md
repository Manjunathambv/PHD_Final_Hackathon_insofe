# PHD_Final_Hackathon_insofe

Flight delay Analysis and Prediction
      Problem Description

Air travel is becoming increasing complex with multiple variables impacting the same. The flight delay is one of such variables impacts carrier, Airport and passenger and may result in significant commercial loss or reputation loss to all the stakeholders and thus huge cost on the economy. Thus, prediction of delay  is crucial not only from view point of customer from time management perspective and carrier for retention of customer faith but also from Airport point of view for managing the traffic more efficiently to optimise the number of arriving flights by appropriate adjustment of schedules. The contribution of weather conditions has been identified to be the very important contributor  of these delays. 
It is of the utmost interest of one of the participants of ecosystem to predict flight delays based on the flights details and predicted weather conditions by a good predictive model, which you are going to build,  to take the necessary corrective and preventive actions to improve business as well as service.  
The historical data containing scheduled departure  and arrival times, date, origin, destination and also weather data is available  and the data scientists can predict if delay can happen or not  using the flight data and aviation weather data for a specific flight.

About Data: 
Every single flight is observed as per their scheduled departure and arrival timestamps, to record the details of trips made, traffic conditions, etc. Flight  details like Origin, destination, date of flight, scheduled departure and scheduled arrival time stamps etc.  Weather stations data details like station id along with it’s linked AirportID, ground height etc. Hourly aviation weather conditions data also provided for 2  years etc.  Origin, Destination details in flight data can be mapped to the AirportID in other datasets.
Objectives: 
I. Derive the Categorical Target Attribute “FlightDelayStatus”:
	1. You are expected to derive the categorical Target attribute 	“FlightDelayStatus” for Train.csv as cited below
II. Predict the flight delay  ‘1’  or  ‘2’    for test set :
	2. You are expected to create an analytical and modelling framework to predict the flight delay  of each id categorizing into “1”  or  ”2”
                    “1” indicates :  “Yes”  and 
                     “2” indicates  : ”No”
Directions to derive the  Target attribute for Train.csv :
1. if the delay is more than  15 minutes then FlightDelayStatus will be “1” else “2”
