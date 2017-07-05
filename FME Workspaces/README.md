# FME Workspaces generated in the course of this project

## Attention 
The Workspaces of phase 1 were generated using FME 2014, the workspaces in phase 2 were generated using FME 2016.1. Opening the Workspaces in different Versions of FME might lead to errors. 
  
## Documentation
The Workspaces of phase 1 were generated using FME 2014, the workspaces in phase 2 were generated using FME 2016.1. Opening the Workspaces in different Versions of FME might lead to errors. Also linsk to data sources (FME Readers) as well as Output paths (FME Writer )need to be adjusted in order to be able to run these FME Workspaces. The data sources are listed [here](https://wiki.tum.de/display/gisproject/Implementation). As some of these datasets are very large, acutally running these workspaces may take several days (depending on the capacity of your PC). 
 
| FME Workspace Nr.   |Short description|
| :-----------: | :----------------------------------|
| 1 |Add additional attributes to the street centerline data generated in project phase 1. Information from different datasets is merged using corresponding attributes such as 'segmentID' or 'gml_name'.|
| 2 |Centerlines representing complex interchanges of motorway junctions are filtered out.|
| 3 |A lod0Network is created using the centerlines generated in (1) and adding sidewalk centerlines as 'Track' features.|
| 4 |Data from the Planimetric Database is manipulated semantically and geometrically. Relevant information contained within the centerline data (generated in 1) is tranferred using a spatial correlation method.|
| 5 |Suitable textures are added to each object generated in (4).|
| 6 |An advanced data structure is implemented by creating 'TrafficAreas' as well as 'AuxiliaryTrafficAreas' and assigning these objects to corresponding 'Road', 'Track' and 'Square' features.| 
| 7 |The output from (6) is textured and extruded to 3D objects.| 
 
