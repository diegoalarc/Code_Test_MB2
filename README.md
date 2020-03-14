!["Uni Wuerzburg"](https://github.com/diegoalarc/Code_Test_MB2/blob/master/Total_Water/EAGLE_logo.png?raw=true "EAGLE Msc")

# Code Test MB2
Here is the project for the MB2 course Introduction to Programming and Geostatistics


Through this script an easy and fast way is proposed to observe the decrease over time of the water level of the Acualeo Lagoon in Chile. It is also possible to modify this code to observe other gaps in the world, using the data provided by [Global SDG database](https://www.sdg661.app/data-products/data-downloads) and a a preset georeferenced area (which can be changed by a Shapefile).

# Scrips

The main __script__ that concerns us in this project is called [Project_Script.R](https://github.com/diegoalarc/Code_Test_MB2/blob/master/Project_Script.R) 
Within this we can find code for:

 - Raster Data of Water Bodies.
 - Copy files to other folders.
 - Tiff files selected by match of a Shapefile in it extent 
 - Select of Tiff images in an automatic form and copy to another folder.
 - Shiny App.
 
The second script that can be seen is called [Project_QGIS_Script.R](https://github.com/diegoalarc/Code_Test_MB2/blob/master/Project_QGIS_Script.R) which was generated to obtain the images that were used for the [QGIS](https://www.qgis.org/en/site/) project of the [Master EAGLE](http://eagle-science.org/) and was intended to work with mosaics at the country level and cut entire regions with memory efficiency. Within this you can find the main up grade with reference to the previous code:

 - Command to call [GDAL](https://gdal.org/) in [QGIS](https://www.qgis.org/en/site/) from [RStudio](https://rstudio.com/)
 - Crop the area from a shapefile without using the temporary file from RStudio.
 - Plot generation and saved directly in a route pre-established by the code.
 
## Script products
 
Here you can see some examples of the images that were generated by applying the [Project_Script.R](https://github.com/diegoalarc/Code_Test_MB2/blob/master/Project_Script.R)
 
 - [i.e. Images for the total water body of the Aculeo Lagoon, which represent the sum of Seasonal and Permanent water bodies](https://github.com/diegoalarc/Code_Test_MB2/tree/master/Total_Water)

!["TimeSeries of Aculeo Lagoon Seasonal Chile between 2000 - 2018 "](https://github.com/diegoalarc/Code_Test_MB2/blob/master/Total_Water/TimeSeries%20of%20Aculeo%20Lagoon%20%20Seasonal%20%20Chile%20.pngraw=true "TimeSeries of Aculeo Lagoon Seasonal Chile between 2000 - 2018")

 - TimeSeries of Permanent Water body for Aculeo Lagoon between 2000 - 2018.

![](https://github.com/diegoalarc/Code_Test_MB2/blob/master/GIF/Permanent.gif)


***
This script was made for testing purposes and can be used and modified in the future by those who deem it convenient.
