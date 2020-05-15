# plotly-dirgraph
Tools for drawing directed network graphs using plotly

**addEdge**
Given two points, generates a line segment connecting these points as well as two line segments forming an arrowhead either in the middle or at the end of these points.

Automatically shortens the line segment length to cover only some fraction of these points if you want to represent your graph edges as arrows rather than conventional network graph edges.

**directed_example**
Uses addEdge to draw a random network graph using plotly.

![directed_example output](https://github.com/redransil/plotly-dirgraph/directed_example.png?raw=true)
