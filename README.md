## Python from Space: Analyzing Open Satellite Imagery Using the Python Ecosystem

This repository contains the slides and Jupyter notebooks for Kat's ["Python from Space"](https://us.pycon.org/2017/schedule/presentation/364/) talk at Pycon 2017 in Portland, Oregon.

### Abstract
Earth imaging satellites, just like our computers, are shrinking and becoming more ubiquitous than ever before. It is now possible to obtain open satellite data on a daily if not weekly basis and for this data to be put to work; helping us better understand our planet and quickly respond to disaster situations.

In this talk, we will work through Jupyter notebooks that cover the satellite data ecosystem and the python tools that can be used to sift through and analyze that data. Topics include python tools for using Open Street Maps data, the Geospatial Data Abstraction Library (GDAL), and OpenCV and NumPy for image processing. This talk is intended for novice and intermediate python developers who are interested in using data science and satellite imagery for social good and fundamental scientific research.

### Contents
* [Slides](Pycon2017.pdf)(pdf for download): An overview of satellites and satellite terminology, the basics of remote sensing, sources of free satellite imagery, and tools for processing and analyzing images.
* [Requirements](requirements.txt): A list of Python libraries you'll need for this project.
* [The Basics](TheBasics.ipynb): Setting up your development environment; making a slippy map and defining an area of interest on the map; searching, filtering, and downloading satellite imagery that intersects with the area of interest.
* [Open Street Map Example](OpenStreetMapExample.ipynb): Querying Open Street Map for all the parks in Porland; finding and downloading satellite imagery of those parks; calculating and analyzing the "greenness" of each park.
* [Making Movies](MovieTime.ipynb): Wayfinding from park to park and creating a masterpiece movie of your "Great Portland Park Tour of 2017."
