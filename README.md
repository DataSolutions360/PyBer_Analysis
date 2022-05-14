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

Below are just some of the procedures and calculations

The approach is to understand the progression from crude calcualtions to aesthetically pleasing presentable graphs and organized data.

As you can see, the city type "RURAL" had the highest average fare per ride, and "UBRAN had the highest total rides and drivers.
This makes sense, due to the fact that RURAL would have a larger origin-to-destination distance.

"URBAN" would have the highest demand for rides, the highest total rides and highest total drivers, 
while still having the lowest fare per driver.

Total rides and total drivers for each city type 

![image](https://user-images.githubusercontent.com/8845050/168445264-d8d49bc1-f056-4439-b520-6a36b3ced055.png)

Total Amount of fares for each city type, Average Fare per Ride for each city type, and Average Fare per driver for each city type

![image](https://user-images.githubusercontent.com/8845050/168445306-92803f74-0aae-4a8b-9b44-e1a295a9303d.png)

Resample function split by Week "W" and aggregate of weekly fares.

![image](https://user-images.githubusercontent.com/8845050/168445424-3dc7bce5-a081-4769-8549-4587bc239183.png)

Cleansing and formatting the Summary to make for aesthetic, professionally legible reporting
This summary demonstrates that URBAN fares, albeit small on average, yield a higher revenue that RURAL.  

## As a Pyber Driver, I would focus on quality, not quantity....better use of my time.

## As a Pyber executive, I would be focused on total revenue, and high demand areas, for sustainability.

![image](https://user-images.githubusercontent.com/8845050/168445745-688a76e9-7a05-4a1d-8e0b-514643068e2c.png)

Using Object-Oriented interface method, we plotted the resample using df.plot() function

This graph displays that "RURAL < SUBURBAN < UBRAN", with respect to revenue.  

![image](https://user-images.githubusercontent.com/8845050/168445379-fa175b2e-8946-43d9-99e8-2f8be5188ded.png)


