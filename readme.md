# Route Maps Builder

By Kenneth Burchfiel

This repository shows how to generate airline route maps using publicly available route and airport data. The route maps have some limitations: for instance, because the data files on which they are based differentiate between mainline (Delta, American, etc.) and regional (SkyWest, Endeavor, etc.) carriers, these maps often fail to show all route data for a particular airline. (See the methodology used to create the map within route_maps_builder_v2.ipynb for more details on the maps' creation.) However, they have the benefit of being entirely open source.

## Screenshots

Here are example screenshots of the route maps currently stored in this repository. (The original route maps are .html files, so for the best viewing experience, I recommend downloading them to your computer and then opening them in a web browser. These screenshots don't display all domestic/North American route data in the original maps.)

**American Airlines Domestic Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/aa_domestic_routes_1999.png?raw=true)



**Note**: The following files were not included in the GitHub repository because their size exceeds 100MB:
1. routes_planes_coordinates.csv
2. routes_planes_coordinates_for_mapping.csv
3. 21503323_T_T100_SEGMENT_ALL_CARRIER.csv
4. routes_planes_coordinates_for_mapping_v2.csv (particularly important for creating the actual route maps)
 
You can instead retrieve these files from my copy of this project on Google Drive, available at https://drive.google.com/drive/folders/1jRTjoZtT6OWCXRTNstG9D4CxmjXe4W8q?usp=sharing .
