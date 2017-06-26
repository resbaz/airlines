# Airlines
This repository contains data on all current airline routes and historical airline collisions data from 1920 to 2016.

There are two csv files. The description of the columns are as follows:

## airline_routes.csv

Current dataset of  all commercial airlines carrying passengers.

- Airline Operator
- Airline ID
- Source Airport
- Source Airport ID
- Destination Airport
- Destination Airport ID
- Codeshare (that is, not operated by Airline, but another carrier)= if yes, then Y. If no, then blank
- Number of stops
- Equipment: 3-letter codes for plane type(s) generally used on this flight, separated by spaces

Routes are directional: if an airline operates services from A to B and from B to A, both A-B and B-A are listed separately.

Routes where one carrier operates both its own and codeshare flights are listed only once.

Data can also be found here: https://openflights.org/data.html

## collisions.csv

- Date
- Operator
- Registration
- AirType: Type of equipment
- Locations: Location of the flight crash
- Aboard: Number of passengers aboard the AirCraft
- fatalities: Number of passengers aboard who died.
- groundfatalities: Number of people on the ground who died.

The data can be found here: http://www.planecrashinfo.com/database.htm




