# QGIS Plugin Project

In this project, a python-based plugin has been developed for QGIS. The purpose of the plugin is to find the distance between selected points with different distance metrics. Two different point selection formats are presented to the user in the plugin. In one of these methods, the user selects the points between which the distance should be found from the plugin interface. Second, points are selected via QGIS. Three different metrics are used to calculate the distance between the selected points in the plugin. These metrics are Euclidean distance, Manhattan distance and Chebyshev distance, respectively.

## Introduction
It allows users to calculate the distance between two points based on different distance
metrics. Users can do the point selection process in two different ways within the plugin.
These ways are:
  1. After adding the layer, selecting the points listed in the table from within the plugin
and finding the distance between them
  2. After selecting the points with Select Feature(s) on the QGIS menu, calculating the
distance between them in the plugin

Three different distance calculation metrics are calculated for the distance between the
selected points in the plugin. These:
  1. Euclidean Distance
  2. Manhattan Distance
  3. Chebyshev Distance
## Requirements
The only requirement is to get QGISv3 or later installed. You can download it from QGIS
official website.
