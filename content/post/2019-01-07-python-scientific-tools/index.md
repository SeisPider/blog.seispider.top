---
title: "Python scientific tools in geoscience" 
date: "2019-01-07"
lastmod: "2019-01-07"
categories: ["Python"] 
tags: ["Tools", "Python"]
draft: false 
author: "Xiao Xiao"
---

As we all know, all data science projects include three parts: retrieving data, numerical 
computation and result visualization. Take seismology as an example, ways for requesting 
seismic data from providers (IRIS, ISC and NIED etc.) are concluded [here](/post/2016-10-30-geophysical-websites/). 

Thus, this post focuses on collecting serveral useful python library for 
general scientific numerial computation and visualization.

<!--more-->
## Visualization

| Library     |  Dimension  |   Figure field  | Note |
| ----------- | ----------- |-----------------| ------|
|[Matplotlib](https://matplotlib.org/) |  2D  | General |-|
|[seaborn](http://seaborn.pydata.org/#)|  2D  | Statistics |-|
|[Altair](https://github.com/altair-viz/altair)| 2D | Statistics |-| 
|[HoloViews](http://holoviews.org/gallery/index.html)| 2D| General|Extension to Matplotlib ...|
|[Bokeh](http://bokeh.pydata.org/en/latest/docs/gallery.html#gallery)| 2D| General|For web interative visualization|
|[gmt-python](https://github.com/GenericMappingTools/gmt-python)|2D|Gerneral| Efficient for plotting maps|

## Change log
- 2019-01-07: Initial version
