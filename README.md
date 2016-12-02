# NYC GIS Metadata
-------------

This document lists metadata sources for data updated and maintained by the NYC Department of Information Technology and Telecommunications (DOITT).

| Data/Layer Name | Description |  Metadata Link | Preview |
| ---|---|---|---|
 | Address Point | Address points were initially created from data in the Department of City Planning Property Address Directory (PAD) file. Points were created approximately five feet inside building footprints along the correct street frontage. A field collection/verification process was undertaken to validate "multi-valued" addresses contained in the PAD file (i.e. those locations with a range of addresses). Additionally, a statistical sample of PAD single valued addresses was field checked. Approximately 100,000 locations were visited (about 10% of the total). | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_AddressPoint.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/AddressPoint.PNG)
 | After-School Programs | The New York City Department of Youth and Community Development offers engaging high quality programs for young people in all five boroughs of New York City during the hours they are not in school. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_AfterSchoolPrograms.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/AfterSchoolProgram.PNG)
 | Agency Service Center | Points representing approximate locations of city agency's Customer Service Centers that are open to the public and provide services and information on various programs. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_AgencyServiceCenter.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/AgencyServiceCenter.PNG)
 | Boardwalk | This feature class contains boardwalk features along the shoreline/beach areas. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Boardwalk.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Images/FeatureViews/Boardwalk.png)
 | Building Footprints | This feature class contains building footprints. Each footprint represents the perimenter extent of the building. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_BuildingFootprints.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Images/FeatureViews/Build_Foot.png)
 | Business Improvement Districts | Polygons representing location of Business Improvement Districts (BIDs). A BID is a public/private partnership in which property and business owners elect to make a collective contribution to the maintenance, development, and promotion of their commercial district.  | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_BIDs.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/BusinessImprovementDistricts.PNG)
 | Contours | Planimetric basemap layer containing citywide 2-ft contour line features | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Contours.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/Contours.PNG)
 | Cooling Towers | Cooling towers are structures typically found on the roofs of large buildings that enclose large fans used for ventilation and cooling. Only cooling towers greater than 4ft in diameter were captured. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Images/FeatureViews/CoolingTower.JPG)
 | Curb | Curbs are represented by segments between pavement and other surfaces. A curb feature is captured where it exists for the streets within ROW only.  | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Curb.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Images/FeatureViews/Curb.png)
 | Digital Elevation Model | The 1 foot Digital Elevation Model (DEM) is from LiDAR captured in April/May 2010.  | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_DigitalElevationModel.md) | ![image](--)
 | Elevation | This feature class contains elevation points throughout the city of the following types: <br>BUILDING ELEVATION - Elevation of the highest portion of the roof of a building, excluding antennae and roof fixtures such as air conditioning (AC), elevator shafts, chimneys, etc.<br>WATER ELEVATION - Elevation on standing water (ponds, reservoirs, lakes).<br>SPOT ELEVATION –Elevation points collected in the center of the roadbed (coincident with CSCL), captured at beginning, mid-point, end, and at 200’spacing of the visible roadbed. Spot elevations are captured on paved, unpaved, alley subtypes in CSCL Centerline and all of Interior Sidewalk Centerline. Spot elevations will not be captured to a CSCL if no roadbed exists.<br>BRIDGE ELEVATION - Elevation points captured at beginning, mid-point, end, and at 200’spacing of the visible bridge deck.  | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Elevation.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Images/FeatureViews/Elevation_Build.png)
 | Greenthumb | As the largest community gardening program in the country, GreenThumb is proud to support community gardens in New York City. There are over 600 member gardens serving 20,000 city residents. Since 1978 GreenThumb has been committed to providing support to help strengthen gardens, strengthen gardener skills, and strengthen communities. GreenThumb's services take the form of materials and technical assistance, including educational workshops. The shapefile includes point representing approximate location of community gardens participating in the NYC Department of Parks & Recreation GreenThumb Program. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Greenthumb.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/Greenthumb.PNG)
 | Historic Districts | This dataset contains boundaries and associated attribute information for all designated historic districts or areas under consideration for historic district designation (i.e. calendared) by the New York City Landmarks Preservation Commission (LPC), including items that may have been denied designation or overturned. Please note that some areas may have multiple records in the database if different actions were taken over time. Please pay close attention to the "CURRENT" and "LAST_ACTION_ON_BOUNDARY" fields to determine the status of a particular area. The geographic locations of the polygons in this dataset are derived primarily from the Department of City Planning's PLUTO dataset, and therefore discrepancies may arise where the LPC dataset has not been updated with information from the most recent PLUTO releases. Please pay close attention to the field descriptions present in the file's metadata to understand how to use this dataset. And please contact LPC if there are questions or concerns | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_HistoricDistricts.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/HistoricDistricts.PNG)
 | Hydro Structure | This feature class contains the following Hydro structures:<br>PIERS = Deck supported by posts extending into the water.<br>JETTY = Structure, usually stone, earth, or concrete extending from shore to lessen erosion, in continuation of river channels at their outlets or into docks, and outside their entrances. Delineated at the water level.<br>SEAWALL = Typically, a seawall is built on the land parallel to the coast, but may also apply to breakwaters that are built into the water. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_HydroStructure.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Pier.png)
 | Hydrography | This feature class contains water bodies (types listed below) and is generally only updated when the actual shape has changed. These are not updated due to different water levels (e.g., high/low tide). This feature class includes the following subtypes:<br>LAKE/RESERVOIR = lake/reservoir hydro features<br>POND = pond hydro features<br>RIVER = river hydro features<br>STREAM = stream hydro features<br>WETLAND/MARSH = wetland/marsh hydro features<br>BEACH/SHORELINE = beach/shoreline hydro features<br>BAY/OCEAN = bay/ocean hydro features | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Hydrography.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Lake.png)
 | Landmarks | This dataset contains information on all items designated or under consideration for designation (i.e. calendared) by the New York City Landmarks Preservation Commission (LPC), including items that may have been denied designation or overturned. The dataset contains records for each individual, scenic, or interior landmark, as well as properties or sites located within the boundaries of historic districts. Please note that points in this dataset represent individual buildings in addition to non-building sites (such as vacant lots or monuments) regulated by LPC. It is possible for a single property to have multiple designations (such as individual and interior designations, or individual and historic district). For this reason, it is not uncommon to see multiple points on a single tax lot and multiple records for a single property within the database. Please pay close attention to the "MOST_CURRENT," "BBL_STATUS and "LAST_ACTION_ON_LP" fields, which together denote the designation status of a site/property (see Attribute Definitions for more information). The geographic locations of the points in this dataset are derived primarily from the Department of City Planning's PLUTO data in combination with the Department of Information Technology & Telecommunication's building footprint information. Because this dataset is not automatically updated when changes occur in the underlying dataset, BIN numbers and tax lot information are potentially out of date. Please pay close attention to the field descriptions present in the file's metadata to understand how to use this data set. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Landmarks.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/Landmarks.PNG)
 | Median | All medians that physically divide a roadbed are collected and include medians, traffic islands, and Jersey barriers as well as painted medians to separate the traffic flow. Medians can be paved and are normally elevated (have a curb) or have dirt or grass. Subtypes include:<br>MEDIAN_PAINTED = Medians that have white paved marking (fishbone or striped) shall be collected as Median-painted. Double yellow lines in the middle of a road are NOT medians. Single independent white medians hatched used to direct traffic are NOT medians.<br>MEDIAN_CURB = Median with curb edge regardless of interior content (grass, pavement, concrete, etc.).<br>MEDIAN_RAIL = Median with guardrail.<br>MEDIAN_FENCE = Median with fence. <br>MEDIAN_GRASS = Median with grass/vegetation inside and no curb.<br>MEDIAN_BARRIER = Jersey barriers must be of “permanent nature,”i.e., in place to regulate the traffic, and must be displayed with a constant width of three (3) feet centered on the barrier. This does not include jersey barriers in construction areas or being used to block-off road access. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Median.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Images/FeatureViews/Median_Painted.png)
 | Misc Struct Poly | This feature class contains various miscellaneous structures including:<br>BILLBOARD = Advertisement sign.<br>SIGN_GANTRY = Traffic information sign crossing traffic lanes (ROW).<br>TOLL PLAZA = Toll booth locations. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_MiscStructPoly.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Sign_Gantry.JPG)
 | NYCHA Developments | Locations of the public housing developments of the New York City Housing Authority. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_NYCHADevelopments.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/NYCHADevelopments.PNG)
 | Open Space | This feature class contains various open areas (with no or few buildings), including:<br>CEMETERY OUTLINE = Boundary of cemetery.<br>RECREATIONAL AREA = areas used for picnic or other recreational use, NOT including NYC designated parks. Recreational areas must contain at least one of the following: Benches, Swings, Play area.<br>VACANT AREA = intended to be a vacant lot where a building could potentially be built and is associated with a tax lot polygon boundary. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_OpenSpace.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Cemetery.JPG)
 | Park | The PARK feature class contains both the PARK BOUNDARY for NYC Department of Parks and Recreation (DPR) designated parks, as well as the following Park features, which are often within (overlapping) the park boundaries.<br>BASEBALL/SOFTBALL FIELD = Baseball or softball fields<br>BASKETBALL COURT = Basketball courts<br>HANDBALL COURT = Handball courts<br>MULTIPURPOSE COURT = Multiuse areas<br>TENNIS COURT = Tennis courts<br>VOLLEYBALL COURT = Volleyball courts<br>FOOTBALL FIELD = Football fields<br>SOCCER FIELD = Soccer fields<br>GOLF COURSE = Golf courses<br>POOLS = Public pool areas<br>TRACK- Running track<br>SKATING RINK = Skating or hockey rink<br>GREENSTREETS = These coincide with DPR Greenstreet dataset. Park adjacent to road.  | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Park.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Park.JPG)
 | Parking Lot | This feature class contains parking lots (paved or unpaved) greater than 2,000 sq. feet. Traffic islands within parking lots are not delineated. This feature class does not include gas stations, private lots, storage areas, etc as parking lots.Additionally, Parking areas adjacent to the travel-way BUT NOT separated from the travel-way by a curb or other obstruction are not parking lots. These parking areas are to be part of the roadbed. Parking areas adjacent to the travel-way AND separated from the travel-way by a curb or other obstruction are parking lots.  | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_ParkingLot.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Parking_Lot.png)
 | Pavement Edge | This feature class contains lines representing the edge of pavement.<br>EDGE OF PAVEMENT - Line features placed between the roadbed and other features (i.e. Curbs, sidewalks, or grass.) Each segment is continuous across a blockface (typically from one intersection to the next –along that side of the road).<br>AIRPORT RUNWAY –Line features representing the outer-edge of all paved airport features, including runways, taxiways and aprons.<br>ALLEY - edge of pavement along narrow unnamed street that allows access to buildings/garages other than from the road.  | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_PavementEdge.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Road_Edge.JPG)
 | Planimetrics | Planimetric mapping is the capture of geographic features from aerial survey that are traditionally mapped in two dimensions. NYC DOITT first developed a planimetric database in 2000. Today, the database includes features for ![Building Footprints](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_BuildingFootprints.md), ![Boardwalk](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Boardwalk.md), ![Cooling Towers](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_.md), ![Curb](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Curb.md), ![Elevation](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Elevation.md), ![Hydro Structure](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_HydroStructure.md), ![Hydrography](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Hydrography.md), ![Median](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Median.md), ![Misc Struct Poly](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_MiscStructPoly.md), ![Open Space](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_OpenSpace.md), ![Park](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Park.md), ![Parking Lot](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_ParkingLot.md), ![Pavement Edge](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_PavementEdge.md), ![Plaza](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Plaza.md), ![Railroad](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Railroad.md), ![Railroad Structure](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_RailroadStructure.md), ![Retaining Wall](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_RetainingWall.md), ![Roadbed](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Roadbed.md), ![Shoreline](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Shoreline.md), ![Sidewalk](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Sidewalk.md), ![Sidewalk Centerline](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_SidewalkCenterline.md), ![Swimming Pool](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_SwimmingPool.md), ![Transport Structure](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_TransportStructure.md), and ![Under Construction](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_UnderConstruction.md). | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Planimetrics.md) | ![image](--)
 | Plaza | This feature class contains plaza features (i.e., hard surfaced "parks") adjacent to public sidewalks or pavement edges in public space. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Plaza.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Plaza_3.JPG)
 | Railroad | This feature class contains the following Railroad features:<br>RAILROAD - Visible and Hidden Railroad centerlines.<br>ELEVATED RAILROAD - Elevated Railroad centerlines.<br>EMBANKMENT RAILROAD- Embankment Railroad centerlines.<br>VIADUCT CENTERLINE- Viaduct Railroad centerlines.<br>DEPRESSION RAILROAD- Open Cut Depression Railroad centerlines.<br>RAILWAY FENCE- Railroad Fencing centerlines.<br>ABANDONED RAILROAD- Abandoned Railroad centerlines. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Railroad.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/RR.JPG)
 | Railroad Structure | This feature class contains the following Railroad structures:<br>SUBWAY/TRAIN STATION - Stand-alone subway and train stations and platforms.<br>ELEVATED SUBWAY/TRAIN STATION - Elevated subway and train stations and platforms.<br>VENTILATION GRATE - Ventilation grates within the ROW area.<br> EMERGENCY EXIT - Emergency Exit locations.<br>TRANSIT ENTRANCE - Entrance locations. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_RailroadStructure.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/RR_sta.JPG)
 | Retaining Wall | This feature class contains the following Retaining Wall features:<br>RETAINING WALL - Walls that retain earth from falling on transportation features.<br>RAILROAD RETAINING WALL - Walls that retain earth from falling on railroad bed. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_RetainingWall.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Retaining_Wall_1.png)
 | Roadbed | This feature class contains the following Roadbed features:<br>ROADBED - Roadbed feature.<br>INTERSECTION - Intersection of roadways.<br>DRIVEWAY - Driveway feature.<br>SHOULDER - Shoulder along roadway. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Roadbed.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Roadbed.JPG)
 | Shoreline | This feature class contains shorelines.  | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Shoreline.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Shoreline.png)
 | Sidewalk | This feature class contains the following Sidewalk features:<br>ROW SIDEWALK - All paved sidewalks that are located along or adjacent to the ROW (i.e. building to building).<br>INTERIOR SIDEWALK - All paved sidewalks for all interior sidewalk that are located interior to the ROW.  The business use of this feature is to identify potential areas, outside of the public Right of Way (ROW), that could permit emergency vehicles through travel. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Sidewalk.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Sidewalk_1.png)
 | Sidewalk Centerline | This feature class contains Interior sidewalk centerlines for all interior sidewalk polygon features but not the ROW-Sidewalk. The business use of this feature is to identify potential areas, outside of the public Right of Way (ROW), that could permit emergency vehicles through travel. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_SidewalkCenterline.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Sidewalk_ln.png)
 | Street Centerline | Centerline is a single line representation of New York City streets containing address ranges and other information such as traffic directions, road types, segment types. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_StreetCenterline.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/StreetCenterline.PNG)
 | Swimming Pool | This feature class contains all in-ground swimming pools, regardless of shape, on the inside (water) of the pool. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_SwimmingPool.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Swimming_Pool.png)
 | Transport Structure | This feature class contains the following Transportation structures:<br>BRIDGE - Structure erected over obstacle for road traffic (road, railroad, hydrography).<br>TUNNEL - Underground throughways.<br>RAIL BRIDGE - Structure erected over obstacle for railroad traffic (road, railroad, hydrography).<br>PEDESTRIAN/BIKE BRIDGE - Structure erected over obstacle for pedestrian and / or bicycle traffic (road, railroad, hydrography).<br>RAILROAD VIADUCT - Bridge composed of several small arches, mostly over water.<br>OVERPASS - Structure erected over road, whereas the lower road has been excavated and has retaining walls on the side. Overpass is at terrain level. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_TransportStructure.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Bridge.JPG)
 | Under Construction | This feature class includes all areas under construction (excavation) or deposits of material (storage) at their outer boundary. | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_UnderConstruction.md) | ![image](https://github.com/CityOfNewYork/nyc-planimetrics/raw/master/Images/FeatureViews/Unk_Construction.png)
 | Wi-Fi Hotspot Locations | This dataset includes public Wi-Fi Hotspot locations throughout the 5 boroughs. Wi-Fi providers include At&T, LinkNYC-Citybridge (BETA), BPL, Cablevision, Chelsea, City Tech, Downtown Brooklyn, Harlem, Manhattan Down Alliance, NYCHA, NYPL, QPL, Time Warner Cable, Transit Wireless, and various partners.  | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_WiFiHotspots.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/WiFiHotspots.PNG)
 | Zip Code Boundaries | This dataset contains boundaries of zip codes within New York City, NY.  | [Metadata](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_ZipCodeBoundaries.md) | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/ZipCodeBoundaries.PNG)
