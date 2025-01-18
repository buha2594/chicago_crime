# chicago_crime
To analyze chicago crime dataset to understand the patterns and derive interpretation from it
The dataset contains 54999 rows of data.
The various columns includes ID, Case Number, Primary type, arrest made,
Domestic or Non domestic, Latitude Longitude etc..
Rows such as Location Description , Ward, Community Area, X Coordinate ,Y Coordinate, Latitude ,Longitude ,Location  contains Null values which needs to be handled
Total 6912 columns does not have 'Latitude', 'Longitude','Location', 'X Coordinate', 'Y Coordinate'values. Making these values as -1  and location to unknown since they represent less than 2% of data
Dropping Ward column since it has too many null values and it is not an essential column for visualization
Used tableau to visualize various trends in the dataset
