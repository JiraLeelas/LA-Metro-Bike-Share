# **Ride Metro Bike Share Data**

## **Information**
Creator: Metro Bike Share (Metro and the City of Los Angeles Partnership)
Origin: Los Angeles, California, United States of America
URL: https://bikeshare.metro.net/about/data/
Collection: 2016 (Q3) - Present

## **Metro Trips Variables**
* trip_id: Locally unique integer that identifies the trip
* duration: Length of trip in minutes
* start_time: The date/time when the trip began, presented in ISO 8601 format in local time
* end_time: The date/time when the trip ended, presented in ISO 8601 format in local time
* start_station: The station ID where the trip originated (for station name and more information on each station see the Station Table)
* start_lat: The latitude of the station where the trip originated
* start_lon: The longitude of the station where the trip originated
* end_station: The station ID where the trip terminated (for station name and more information on each station see the Station Table)
* end_lat: The latitude of the station where the trip terminated
* end_lon: The longitude of the station where the trip terminated
* bike_id:  Locally unique integer that identifies the bike
* plan_duration: The number of days that the plan the passholder is using 
entitles them to ride; 0 is used for a single ride plan (Walk-up)
* trip_route_category: "Round Trip" for trips starting and ending at the same station or "One Way" for all other trips
* passholder_type: The name of the passholder's plan
* bike_type: The kind of bike used on the trip, including standard * pedal-powered bikes, electric assist bikes, or smart bikes.

##  **Station Variables**
* Station ID: Unique integer that identifies the station (this is the same ID used in the Trips and Station Status data)
* Station Name: The public name of the station. "Virtual Station" is used by staff to check in or check out a bike remotely for a special event or in a situation in which a bike could not otherwise be checked in or out to a station.
* Go live date: The date that the station was first available
* Region: The municipality or area where a station is located, includes DTLA (Downtown LA), Pasadena, Port of LA, Venice
* Status: "Active" for stations available or "Inactive" for stations that are not available as of the latest update


**Last Update:** 11/03/2025

