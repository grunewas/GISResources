# Resources for Getting Started with Geographic Information System (GIS) Mapping  
by Susan Grunewald

Updated: 09/30/2019

## DATA SOURCES:
DIVA-GIS is a source of both open source mapping software and data sets  
including country boundaries, population density, roads and climate data.
	http://www.diva-gis.org/
Check out this blog for a breakdown of free data organized by nation-state.
	https://dragons8mycat.com/gis-data-sources/

## OPTICAL CHARACTER RECOGNITION (OCR): 
If you have a series of locations that you need to scan from a book, you can use  
the process of OCR to turn the jpeg images of the scan back into text. You can  
then map the locations either by following steps for GEOCODING below to turn the  
place names into coordinates for use with mapping software or websites, or see  
the steps for GEOPARSING below.

### Adobe Acrobat Pro has an OCR feature in it.
 -  https://acrobat.adobe.com/us/en/acrobat/acrobat-pro.html) 
 -  https://acrobat.adobe.com/us/en/acrobat/how-to/ocr-software-convert-pdf-to-text.html
### ABBYY FineReader is another paid OCR program that works well.
 -  https://www.abbyy.com/en-me/finereader/ 
### Tabula is opensource and web-based. It works well to OCR text in tabular format.
 -  https://tabula.technology/

## GEOCODING:
When you want to map places, most mapping programs will require a series of  
latitude and longitude coordinates.

If you want to get the coordinates for up to 100 locations, simply copy and  
paste to use the use the Google Map Developers Batch Geocode Tool.
	https://www.mapdevelopers.com/batch_geocode_tool.php
If you need to geolocate larger numbers of locations, I suggest using ggmap for  
R if you have some basic coding skills. 
	https://cran.r-project.org/web/packages/ggmap/ggmap.pdf 

## GEOPARSING:
If you merely want to produce a quick map with locations mentioned in a text,  
such as a novel for example, you can upload the .txt file to Recogito.
	https://recogito.pelagios.org/

For a tutorial for how to do geoparsing with a different web program, the  
Edinburgh Geoparser, see this tutorial from the excellent website The  
Programming Historian:
	https://programminghistorian.org/en/lessons/geoparsing-text-with-edinburgh 

## WEB MAPPING:
One of the most basic mapping tools is National Geographic’s MapMaker  
Interactive.
	https://mapmaker.nationalgeographic.org/

A great, easy to use mapping program that allows you to export static maps is  
keplr.gl
	https://kepler.gl/

More advanced maps and story maps can be made with Esri’s ArcGIS Online.
	https://www.arcgis.com/home/index.html

## DESKTOP MAPPING SOFTWARE:
More complicated maps are generally created with desktop software.

The open source QGIS is one of the best known open source mapping programs.
	https://www.qgis.org/en/site/

There are a number of great tutorials for getting started with an using QGIS.  
I recommend Seth Bernstein’s two-part series on getting and cleaning historical  
data and then mapping and analyzing it in QGIS.
	http://www.abstractualized.com/2015/10/how-to-map-gulag-data.html
	http://www.abstractualized.com/2015/11/how-to-map-gulag-visualizing.html
	
The Geospatial Historian is an online textbook with great tutorials for both QGIS and ArcGIS.
	https://geospatialhistorian.wordpress.com/lessons/

Lincoln Mullen's Spatial Humanities Workshop also has helpful information for getting started with QGIS as well as other aspects of spatial humanities and various mapping interfaces.
	https://lincolnmullen.com/projects/spatial-workshop/
	
The Programming Historian has a series of tutorials for an older version of QGIS  
as well ranging from installing the software to georeferencing (taking scans of  
old maps and then layering data on top), creating new vector layers, and  
geocoding historical data.
	https://programminghistorian.org/en/lessons/qgis-layers
	https://programminghistorian.org/en/lessons/georeferencing-qgis
	https://programminghistorian.org/en/lessons/vector-layers-qgis
	https://programminghistorian.org/en/lessons/geocoding-qgis

The highest level GIS software is Esri’s ArcGIS Pro. It is an extremely stable  
and versatile program that allows users to analyze data in a variety of ways.  
Licenses are extremely expensive, but if you are based at a university or   
college, your school might have a license that you can use.
https://pro.arcgis.com/en/pro-app/ 
	
