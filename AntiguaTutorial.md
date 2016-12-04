# Antigua Maps
### Author: John.Harris@mavs.uta.edu
## This excercise allows you to apply the skills learned in the Barbados exercise to Antigua.

1. Make a folder entitled "Antigua" on your computer.
2. Go to [DIVA GIS](http://www.diva-gis.org/gdata) and download the shapefiles for the administrative districts and roads of Antigua and Barbuda.
3. Open and extract the files within the new "Antigua" folder.
4. Open QGIS and begin a new project.
5. Set up "On the Fly" CRS.  Choose the **Geographic Coordinate Systems** "Antigua 1943" for your coordinates.
![CRS](https://github.com/HIST5360-f16/QGIS1-Antigua/blob/master/ScreenshotAntiguaCRS.png?raw=true)
6. Build the basemap by opening the following vectors:
 * ATG_adm1; remove color fill or choose color that allows for some transparency and contrast with other colors.
 * ATG_roads; add as a vector layer.
 ![Base Map](https://github.com/HIST5360-f16/QGIS1-Antigua/blob/master/ScreenshotAntiguaBase.png?raw=true)
7. Import "Antigua 1775" and "Antigua 1824" from JCH3 on Github into your Antigua folder.
8. Add "Antigua 1775" as raster layer. Adjust transparency so that you can see the base map and old map in contrast. Or move the map layers to the bottom of the list in the layers panel so bothe can be seen.![layers](https://cloud.githubusercontent.com/assets/22089290/20863395/8c5a0c00-b98e-11e6-8b47-341945d0430b.png)
9. Unselect the "Antigua 1775" and add the "Antigua 1824" as a raster layer. Now you can switch back and forth between late eighteenth-century and early nineteenth-century cartographic conceptions of Antigua. Yay!![1824](https://cloud.githubusercontent.com/assets/22089290/20863433/b40864ee-b98f-11e6-85c9-c30f918308e8.png) ![1775](https://cloud.githubusercontent.com/assets/22089290/20863437/c5e986b6-b98f-11e6-8a16-dd1cbca2e76a.png)
10. Save your work and close QGIS.
