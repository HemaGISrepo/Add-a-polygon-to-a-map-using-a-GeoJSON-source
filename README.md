# Add-a-polygon-to-a-map-using-a-GeoJSON-source

This example adds a polygon to a map, then colors it blue and makes it slightly transparent.

Upon loading, the map uses addSource to add GeoJSON data containing one polygon that outlines the state of Maine. Then it uses addLayer to create a new fill layer and applies paint properties to style the polygon's appearance. To add an outline around the polygon, it uses addLayer again to create a new line layer referencing the same GeoJSON source.


![image](https://user-images.githubusercontent.com/118595650/202859494-d9c305c7-d697-41cf-a63d-2a1547075bc5.png)
