# Total-Species-in-Hertfordshire-2023

Total Bird Species recorded in the County of Hertfordshire for 2023. A static version of the map is available at: https://www.hnhs.org/herts-bird-club/data Grid references from Hertfordshire Bird Club records for the entirity of 2023 were converted into eastings and northings using R 4.4.1 package rnrfa_2.1.0.6 tool osg_parse. These were then imported into QGIS 3.34.10-Prizren​ and "Count points in Polygons" used to count up the total number of species per OS 1km grid square using the Group by to allow multiple records of the same species to only contribute one to the overall count. The polygon layer used was OS 1km grid squares from GitHub which were clipped to the County Boundary of Hertfordshire which resulted in 1821 squares. No records outside the county boundary contribute to this map. No records with a grid reference of less than four figures contributes to this map. 

Programs to make the map: qgis2web and Leaflet in QGIS 
Basemap: OpenData StreetView Contains OS data © Crown copyright and database right 2023.
Data: Bird species data for 2023 derived from 283,737 records from the Herts Bird Club Database (Hertfordshire Bird Club, 2024).
OS 1 km grids derived from Ordnance Survey GitHub https://github.com/charlesroper/OSGB_Grids/tree/master?tab=readme-ov-file. 
Hertfordshire County and District Boundaries downloaded from Mapit https://mapit.mysociety.org/areas/DIS.html and is Ordnance Survey data © Crown copyright and database rights; NISRA data © Crown copyright; Royal Mail data © Royal Mail copyright and database rights (Code-Point Open); National Statistics data © Crown copyright and database rights (ONSPD)., Places with a population greater than 1000 are labelled with data derived from OpenSoft https://public.opendatasoft.com/explore/dataset/geonames-all-cities-with-a-population-1000/export/?disjunctive.country&refine.country=United+Kingdom&disjunctive.cou_name_en

Excellent guidance for producing and publishing qgis2web maps to GitHub https://www.youtube.com/watch?v=JEzKWHdi49o and https://www.youtube.com/watch?v=zlBsiuhYVps.

Summary Statistics for 2023

Most species: 142 in TL3712 <br />
Percentage of squares with at least one species recorded: 67% <br />
Mean Number of Species per Square: 14 <br />
Mean Number of Species per Square (excluding 0'species): 21 <br />
Median Number of Species per Square: 3 <br />
Median Number of Species per Square (excluding 0'species): 12
