# Asheville Alcohol Producers Map

I created this map using a custom made dataset, a Zoning District Shapefile from Asheville's Open Data portal. 

The custom dataset was created using AVLToday's "The Ultimate List of Breweries in Asheville" as well as Asheville Ale Trail's list of distilleries in Asheville. These were compiled into an Excel file and given a Type based on the prominent type of alcohol production. 
- Cideries: breweries that exclusively make Cider or none-wheat beer (Ginger beer).
- Distilleries: exclusively distill alcohol.
- Breweries: Catch all (even if cider is brewed as well)
Lat and Long coordinates were taken from Google Maps. 

Zoning District Shapefile was taken from Asheville's Open Data portal. File was converted to GeoJson using GeoJSON.io which was also used to create an attribute for total alcohol producers in the zone (total_alc) which was used for the chloropleth map.

