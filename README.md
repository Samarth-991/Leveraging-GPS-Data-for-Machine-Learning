# Leveraging-GPS-Data-for-Machine-Learning
Location data is an important category of data that you frequently have to deal with in many machine learning applications. Location data typically provides a lot of extra context to your application’s data.This repo talks about how to process data and pre-process GPS information for ML-DL pipelines.

This repository contains code and jupyter notebooks with machine learning algorithms for working with GPS trajectories.
The dataset used is the popular GeoLife GPS Trajectories

## Geospatial data formats

There are a number of standard formats. They store geometry data along with other descriptive attributes about geographical entities. For instance, they could store route coordinates for roads along with the road surface, width, speed limit, type (city street, highway, etc).

Some of the most commonly used formats are:

    Shapefile (oldest and most widely used standard. A single ‘shapefile’ actually consists of a set of files — one file stores geometry data, another file stores custom data attributes, etc)
    GeoPackage (newer spec that is gaining popularity. Captures data in a single lightweight SQLLite database file with multiple layers)
    GeoJSON (uses standard text-based JSON format)

## Data: 
This GPS trajectory dataset was collected in (Microsoft Research Asia) Geolife project by 182 users in a period of over five years (from April 2007 to August 2012). A GPS trajectory of this dataset is represented by a sequence of time-stamped points, each of which contains the information of latitude, longitude and altitude. Please refer guide for more information.


## Heatmap Analysis
The Heatmap describes density of the various Routes within Bejing city and will help to understand the Dense road traffic because of any particular mode of Transport

![Image text](https://github.com/Samarth-991/Leveraging-GPS-Data-for-Machine-Learning/blob/main/Heatmap.png)
