# Route Maps Builder

By Kenneth Burchfiel

This repository shows how to generate airline route maps using publicly available route and airport data, along with the Folium and Selenium Python libraries. 

The route maps have some limitations: for instance, because the data files on which they are based differentiate between mainline (Delta, American, etc.) and regional (SkyWest, Endeavor, etc.) carriers, these maps often fail to show all route data for a particular airline. In addition, most maps only show routes for which at least 50 departures were recorded in the BTS data file for that year. However, they have the benefit of being entirely open source. (See the methodology used to create the map within route_maps_builder_v2.ipynb for more details on the maps' creation.)

## Screenshots

Here are example screenshots of the route maps currently stored in this repository. (The original route maps are .html files, so for the best viewing experience, I recommend downloading them to your computer and then opening them in a web browser. These screenshots don't display all domestic/North American route data in the original maps.)

By downloading and modifying this program, you can generate far more route maps than these!

**American Airlines Domestic Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/aa_domestic_routes_1999.png?raw=true)


**American Airlines Domestic Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/aa_domestic_routes_2018.png?raw=true)

**American Airlines International Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/aa_international_routes_1999.png?raw=true)


**American Airlines International Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/aa_international_routes_2018.png?raw=true)


**Alaska Airlines Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/as_all_routes_2018.png?raw=true)


**JetBlue Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/b6_all_routes_2018.png?raw=true)

**Continental Airlines Domestic Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/co_domestic_routes_1999.png?raw=true)

**Continental Airlines International Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/co_international_routes_1999.png?raw=true)


**Delta Domestic Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/dl_domestic_routes_1999.png?raw=true)


**Delta Domestic Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/dl_domestic_routes_2018.png?raw=true)


**Delta International Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/dl_international_routes_1999.png?raw=true)


**Delta International Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/dl_international_routes_2018.png?raw=true)

**Delta Widebody Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/dl_widebody_routes_2018.png?raw=true)

**Frontier Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/f9_all_routes_2018.png?raw=true)


**FedEx Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/fx_all_routes_2018.png?raw=true)

**Allegiant Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/g4_all_routes_2018.png?raw=true)

**Spirit Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/nk_all_routes_2018.png?raw=true)

**Northwest Domestic Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/nw_domestic_routes_1999.png?raw=true)

**Northwest International Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/nw_international_routes_1999.png?raw=true)


**SkyWest Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/oo_all_routes_2018.png?raw=true)


**TWA Domestic Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/tw_domestic_routes_1999.png?raw=true)

**TWA International Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/tw_international_routes_1999.png?raw=true)


**United Domestic Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/ua_domestic_routes_1999.png?raw=true)


**United Domestic Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/ua_domestic_routes_2018.png?raw=true)

**United International Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/ua_international_routes_1999.png?raw=true)


**United International Routes (2018)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/ua_international_routes_2018.png?raw=true)

**US Airways Domestic Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/us_domestic_routes_1999.png?raw=true)

**US Airways International Routes (1999)**
![](https://github.com/kburchfiel/route_maps_builder/blob/master/folium_map_screenshots/us_international_routes_1999.png?raw=true)




**Note**: The following files were not included in the GitHub repository because their size exceeds 100MB:
1. routes_planes_coordinates.csv
2. routes_planes_coordinates_for_mapping.csv
3. 21503323_T_T100_SEGMENT_ALL_CARRIER.csv
4. routes_planes_coordinates_for_mapping_v2.csv (particularly important for creating the actual route maps)
 
You can instead retrieve these files from my copy of this project on Google Drive, available at https://drive.google.com/drive/folders/1jRTjoZtT6OWCXRTNstG9D4CxmjXe4W8q?usp=sharing .
