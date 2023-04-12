# Vector and Raster Analysis

This project demonstrates how to clip images to an area of interst and then merge them into a single file. In a jupyter notebook, I walk through the steps of extracting the geometry for our area of interest, clipping images to the boundary of the area of interst, and the merging all the clipped tiles together.

The "data" folder for the project contains the shapefile "mdi.shp" that serves as our area of interst. The "tiles/boundaries" folder contains the shapefile "boundaries.shp" that contains the bounding geometry for a series of NAIP images. The folder "tiles/img" stores the raw NAIP image files. The folder "tiles/clipped" stores the clipped images, and the folder "tiles/mosic" contains the merged clipped imagery file. The "environment.yml" file contains a list of all the python packages that the code requires to work.

