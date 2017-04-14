# bubble-chart
Qlik Sense Bubble Chart Extension
======================================

This extension visualizes grouping data capability between two dimensions using interactive bubbles. For the grouping of the bubbles the d3 and d3plus visiualization library is used. Every group of bubbles contains a number of limited bubbles to have the grouping effect, represented as an adjacency matrix. Currently a depth of 1 is supported. The size of each bubbles is influenced by a specified measure. All aggregation and rendering is done client-side in JavaScript. Built with Alexander Simoes <a href="https://github.com/alexandersimoes/d3plus">d3plus.js</a> visualization library, published with the MIT open-source license.

![alt tag](https://github.com/pamaxeed/bubble-chart/blob/master/BubbleChart.gif?raw=true)

![alt tag](https://github.com/pamaxeed/bubble-chart/blob/master/BubbleChart_Settings.gif?raw=true)

### Tested on
1. Qliksense Desktop version 3.2 -> http://localhost:4848/hub

### Dimensions:
1. Primary Dimension represents the grouping bubbles
2. Secondary Dimension represents the bubbles inside the grouped one

### Dimensions Custom Properties:
1. Color -> by hex decimal code (please note color settings in the general settings sections when set overrides the color properties set on dimension level)

Hint: dimensions should not contain null values

### Measures:
1. Size KPI (Measure)

### Options:
1. Color by (Primary Dimension, Secondary Dimension, Expression)
2. Show Legend
3. Loading Message
3. Min Bubble Size -> accepted value 1 - 100

### ToDo List:

1. Lasso Selection
2. Add additional cusomizable layout properties
3. Improve coloring 

### Known Issue:

1. Extension can handle a finite number of bubbles -> Not suitable for every usecase
2. Measure Legend issue when using Qliksense Desktop

## Author

**Patric Amatulli**

+ [https://www.linkedin.com/in/patricamatulli/](https://www.linkedin.com/in/patricamatulli/)
* [axeed AG](http://www.axeed.ch)
* [github.com/pamaxeed](http://github.com/pamaxeed)

## License

Copyright © 2017 Patric Amatulli

Released under the MIT license.

***
