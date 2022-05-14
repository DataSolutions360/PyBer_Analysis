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

![image](https://user-images.githubusercontent.com/8845050/168444810-59bed84f-a5b7-4c32-8962-8715375b4da6.png)

Average Far per Driver Per City Type
![image](https://user-images.githubusercontent.com/8845050/168445116-1327bd19-eb58-4f7d-8ac2-1a5805374f17.png)

