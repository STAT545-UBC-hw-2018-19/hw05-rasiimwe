# STAT545A Homework 5 Repository of Rebecca Asiimwe 

## Theme: Factor and figure management

### Assignment overview
[<img align ="right" src="https://github.com/STAT545-UBC-students/hw05-rasiimwe/blob/master/Plugins/plotlygm.gif" width="400" height="250"/>](https://github.com/STAT545-UBC-students/hw05-rasiimwe/blob/master/Plugins/plotlygm.gif)

[Factors](https://www.stat.berkeley.edu/~s133/factors.html) are variables that take on a number of different values and are often refered to as categorical variables. Factors in R are stored as a vector of integer values with a corresponding set of character values to use when the factor is displayed. Both numeric and character variables can be made into factors, but a factor's levels will always be character values. The levels of a factor are used when displaying the factor's values and can be changed when creating a factor by passing a vector with the new values through the labels= argument. 

&nbsp;

**One of the most important uses of factors is in statistical modeling;** since categorical variables enter into statistical models differently than continuous variables, storing data as factors insures that the modeling functions will treat such data correctly.
[<img align ="left" src="https://github.com/STAT545-UBC-students/hw05-rasiimwe/blob/master/Plugins/Capturex.png" width="200" height="200"/>](https://github.com/STAT545-UBC-students/hw05-rasiimwe/blob/master/Plugins/Capturex.png)

#### Assignment Goals:

* Reorder a factor in a principled way based on the data and demonstrate the effect in arranged data and in figures.
* Write some data to file and load it back into R.
* Improve a figure (or make one from scratch), using new knowledge, e.g., control the color scheme, use factor levels, smoother mechanics.
* Make a plotly visual.
* Implement visualization design principles.


To my awesome guests to my repo, please visit [howework1](https://github.com/STAT545-UBC-students/hw01-rasiimwe) and [howework2](https://github.com/STAT545-UBC-students/hw02-rasiimwe/blob/master/hw02.md) for a background on the gapminder dataset. In here I show the exploration, manipulation and analysis of the gapminder dataset. [Homework3](https://github.com/STAT545-UBC-students/hw03-rasiimwe/blob/master/hw03-rasiimwe.md) will walk you through concepts needed for  data manipulation and exploration using dplyr and the subsequent application of ggplot2 to accomplish data and visualization tasks. [Homework4](https://github.com/STAT545-UBC-students/hw04-rasiimwe)explores deeper aspects of data wrangling by working with aggregation and data reshaping to put data in shapes that best fit and support the data analysis tasks at hand by focusing on the usage of functions such as gather(), spread(), mutating joins, filtering joins, set operations and biding datasets.


### For this assignment, please visit the following files :point_down::

|   **Homework Files**   | **Description** |
|----------------|------------|
|[Link to homework5](http://stat545.com/Classroom/assignments/hw05/hw05.html)|This file contains homework 5 tasks and their descriptions|
|[README.md](https://github.com/STAT545-UBC-students/hw05-rasiimwe/blob/master/README.md)|This readme.md file provides an overview of the ghist of this repo and provides useful pointers to key files in my homework-5 repo. Herein, are also links to past files that provide an introduction to data exploration and analysis |
|**[Link to homework-05](https://rasiimwe.github.io/html_render//hw05-rasiimwe.html)**|This html file contains the exploration of factor and figure management concepts. This includes concepts such as reordering factors, improving plot visualizations and working with files, that is, saving and loading objects created with R - by using functions such as `saveRDS()` and `readRDS()`|


