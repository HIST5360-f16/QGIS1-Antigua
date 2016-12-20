# Antigua Maps
![Antigua Flag](https://upload.wikimedia.org/wikipedia/commons/thumb/8/89/Flag_of_Antigua_and_Barbuda.svg/1024px-Flag_of_Antigua_and_Barbuda.svg.png)
### Author: John.Harris@mavs.uta.edu, Modifications by Amber Jolly and Willie Kingren
## This excercise allows you to apply the skills learned in the Barbados exercise to Antigua.

1. Make a folder entitled "Antigua" on your computer.
2. Go to [oas.org](http://www.oas.org/pgdm/data/gis_data.htm) and download both basemap information I and basemap information II for Antigua.
3. Open and extract the files within the new "Antigua" folder.
4. Open QGIS and begin a new project.
5. Set up "On the Fly" CRS.  Choose the **Geographic Coordinate Systems** "Antigua 1943" for your coordinates.
![Antigua CRS](http://i1092.photobucket.com/albums/i405/finbar01/Anitgua%20CRS_zpsrihkzqq3.png)
6. Build the basemap:
 * Add vector layer acoast.shp; remove color fill or choose color that allows for some transparency and contrast with other colors.
 * Add vector layer antroad.shp choose color that allows for some transparency and contrast with other colors.
 ![Antigua Raods and Coastline](http://i1092.photobucket.com/albums/i405/finbar01/antigua%20roads%20and%20cosastline_zpsmddqs1km.png)
7. Import "Antigua 1775" and "Antigua 1824" from JCH3 on Github into your Antigua folder.
8. Georefrence "Antigua 1775" to your shape files. Adjust transparency so that you can see the base map and old map in contrast.
![Antigua georefrenced](http://i1092.photobucket.com/albums/i405/finbar01/Anigua%20georefrenced_zpsx5d5td7g.png)
9. Unselect the "Antigua 1775" and add the "Antigua 1824" as a raster layer by Georefrencing it as well. Now you can switch back and forth between late eighteenth-century and early nineteenth-century cartographic conceptions of Antigua. Yay!
10. Save your work and close QGIS.
#Data Sources
1. Basemaps http://www.oas.org/pgdm/data/gis_data.htm
2. Historic Maps https://github.com/HIST5360-f16/QGIS1-Antigua