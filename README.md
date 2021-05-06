# Creating Zoning Maps Using Python & Pandas
-Evan Collins  
-IDCE 30274  
Link to final carto map: https://skievanc.carto.com/builder/538b6060-5da3-4d5f-8a05-4c6d2940d038/embed  
  
In this tutorial we create a map of zoning exempt parcels by zoning type that provide affordable housing. We first collect the files we need, 1 shapefile and 2 csvs. 
We bring these into python as dataframes using pandas and geopandas. Once we have done this we can merge the dataframes together to have all of our data in one frame. This
makes it possible to make the map we want to. Once we have done this we can export the dataframe as a shapefile. 
At this point we go over to Carto to make a nice looking map. I did not change many of the base setting as I thought they looked nice. I set the symbology as zone_cat so that
each polygon is identifiable as its zoning type. The map shows all the exempt polygons providing affordable housing, with the addition of having each polygon colored based on its zoning. There is also a legend to reference the color.  
I have not used Carto before this, I thought it was quite sleek and easy to use. I have used pandas before, but not geodataframes, I thought that was a nice way to manage
the data. This was a simple way to create a informative map. 



