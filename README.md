# NYC-Taxi-Fare-Estimation-using-Regression

## Objective
New York City Taxi and Limousine Fare - Predicting your fare for the next ride with respect to parameters like Trip Distance, pick up, Drop off time, etc.

New York City Taxi and Limousine Commission (TLC) is an agency responsible for licensing and regulating New York City's taxi cabs and for-hire vehicles.

The TLC data comes from over 200,000 taxi and limousine licensees, making approximately one million combined trips per day.

Column name and Description

ID: Trip identification number<br/>
VendorID: A code indicating the TPEP provider that provided the record. 1= Creative Mobile Technologies, LLC; 2= VeriFone Inc.<br/>
tpep_pickup_datetime: The date and time when the meter was engaged.<br/>
tpep_dropoff_datetime: The date and time when the meter was disengaged.<br/>
Passenger_count: The number of passengers in the vehicle. This is a driver-entered value.<br/>
Trip_distance : The elapsed trip distance in miles reported by the taximeter.<br/>
PULocationID : TLC Taxi Zone in which the taximeter was engaged<br/>
DOLocationID : TLC Taxi Zone in which the taximeter was disengaged<br/>
RateCodeID : The final rate code in effect at the end of the trip. 1= Standard rate 2=JFK 3=Newark 4=Nassau or Westchester 5=Negotiated fare 6=Group ride<br/>
Store_and_fwd_flag: This flag indicates whether the trip record was held in vehicle memory before being sent to the vendor, aka “store and forward,” because the vehicle did not have a connection to the server. Y= store and forward trip N= not a store and forward trip<br/>
Payment_type : A numeric code signifying how the passenger paid for the trip. 1= Credit card 2= Cash 3= No charge 4= Dispute 5= Unknown 6= Voided trip<br/>
Fare_amount : The time-and-distance fare calculated by the meter.<br/>
Extra : Miscellaneous extras and surcharges. Currently, this only includes the USD 0.50 and USD 1 rush hour and overnight charges.<br/>
MTA_tax : USD 0.50 MTA tax that is automatically triggered based on the metered rate in use.<br/>
Improvement_surcharge : USD 0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015.<br/>
Tip_amount : This field is automatically populated for credit card tips. Cash tips are not included.<br/>
Tolls_amount : Total amount of all tolls paid in trip.<br/>
Total_amount : The total amount charged to passengers. Does not include cash tips.<br/>
