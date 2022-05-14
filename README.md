# Pyber Analysis
The purpose of this exploratory data analysis is to identify key ride sharing metrics by type of city 
and create a graphical representation fo the total weekly fares based on the city types which will help 
improve access to ride sharing services and determine ride affordability.

## Technical Analysis

The following "slices" were analyzed to obtain further insight by the following factors:

    - Total Drivers
    - Total Rides
    - Total Fares
    - Average Fares Per Ride

- Using the GROUPBY function, we were able to group the fares by city and data.  This was placed in a data frame using the DataFrame function
- Loc function was used to organize the pivot table within the given date range
- The Copy function was used to create the city type and fare columns.  This was to create a new Data Frame.
- Index Function was used to set and re-set the date time index
- The pivot table was resampled using the Resample and Sum Functions
- Info Function was used to check the index on the new data frame

## Results

Average Fare per Driver Per City Type

![image](https://user-images.githubusercontent.com/8845050/168445116-1327bd19-eb58-4f7d-8ac2-1a5805374f17.png)

Total rides and total drivers for each city type 

![image](https://user-images.githubusercontent.com/8845050/168445264-d8d49bc1-f056-4439-b520-6a36b3ced055.png)

Total Amount of fares for each city type, Average Fare per Ride for each city type, and Average Fare per driver for each city type

![image](https://user-images.githubusercontent.com/8845050/168445306-92803f74-0aae-4a8b-9b44-e1a295a9303d.png)

