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

| Library     |  Dimension  |  Field  | Note |
| ----------- | ----------- |-----------------| ------|
|[Matplotlib](https://matplotlib.org/) |  2D  | General |-|
|[seaborn](http://seaborn.pydata.org/#)|  2D  | Statistics |-|
|[Altair](https://github.com/altair-viz/altair)| 2D | Statistics |-| 
|[HoloViews](http://holoviews.org/gallery/index.html)| 2D| General|Extension to Matplotlib ...|
|[Bokeh](http://bokeh.pydata.org/en/latest/docs/gallery.html#gallery)| 2D| General|For web interative visualization|
|[gmt-python](https://github.com/GenericMappingTools/gmt-python)|2D|Gerneral| Efficient for plotting maps|
|[GMSimViz](https://github.com/ucgmsim/GMSimViz)|3D|automation tool that produces an animated 3D visualization of geological faults, ground motion and other earthquake related data.| Depend on GMT|


## Numerical computation

| Library     |  Note |
| ----------- | ------|
|[Scipy](http://www.scipy.org/ SciPy )|Includes modules for linear algebra, optimization, integration, special functions, signal and image processing, statistics, genetic algorithms, ODE solvers, and others|
|[sympy](http://www.sympy.org/)|Symbolic mathematics.|
|[ad](https://pypi.org/project/ad/)|easily and transparently perform first and second-order automatic differentiation. |
|[Pandas](https://github.com/pandas-dev/pandas)|flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data.|
|[PyKrige](https://pypi.org/project/PyKrige/)|2D/3D kriging interpolation tool|

## References
- [Numerical and scientific python](https://wiki.python.org/moin/NumericAndScientific)

## Change log
- 2019-01-07: Initial version
