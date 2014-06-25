Cho Oyu and Ngozumpa Glacier
============================

Cho Oyu, 6th highest mountain in the world, and the Ngozumpa glacier
below it. Model has 4 quadrants (NW, NE, SW, SE) including Cho Oyu and
the north end of Ngozumpa (NW), the southern end of Ngozumpa (SW), and
two quadrants to the east including Mt. Everest (NE and SE). I printed
the NW and SW quadrants for a friend's expedition to study the
glacier.

See [Mt. Everest from SRTM Data](https://github.com/bld/Mt-Everest-from-SRTM-Data) for instructions on making your own.

This model is [public domain](http://creativecommons.org/licenses/publicdomain/).

Instructions
------------

The models were produced using Shuttle Radar Topography Mission 90-m
resolution data. I am posting Blender models - as displacement maps
and as meshes - as well as the STL files. STL files are scaled for
printing on a Makerbot Cupcake CNC with recessed screws.

I used all open source tools:

* Geospatial Data Abstraction Library (GDAL) to convert SRTM HGT files
  to GEOTIFF
* GIMP to crop the GEOTIFFs
* Blender to produce displacement maps from the GEOTIFFS and meshes
* Meshlab to close the holes

I found that the default scale of the Blender displacement maps was
too flat. I did a test print and used calipers to get the scale
right. Each pixel in X/Y is 90-m. To get the vertical relief correct,
I measured the height of known parts of the map (summit of Cho Oyu and
a nearby valley) and compared this to terrain maps in Google maps and
the width of the model (200 pixels multiplied by 90m).
