# *H-Tree Construction*

An H-tree is a geometric shape that consists of a repeating pattern resembles the letter “H”.

It can be constructed by starting with a line segment of
arbitrary length, drawing two segments of the same length at right
angles to the first through its endpoints, and continuing in the same
vein, reducing (dividing) the length of the line segments drawn at each
stage by √2.

Here are some examples of H-trees at different levels of depth:

[![](https://camo.githubusercontent.com/147ce819b5d3f1f37c00fc74db579c17f9add5ab61586385fbc5273983a1be81/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d6730332e706e67)](https://camo.githubusercontent.com/147ce819b5d3f1f37c00fc74db579c17f9add5ab61586385fbc5273983a1be81/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d6730332e706e67)[![](https://camo.githubusercontent.com/d3f0ca406085259132c6b4155b83d7b6981e7c5b883f0f16147192d0cde727e0/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d6730342e706e67)](https://camo.githubusercontent.com/d3f0ca406085259132c6b4155b83d7b6981e7c5b883f0f16147192d0cde727e0/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d6730342e706e67)
[![](https://camo.githubusercontent.com/cd166e549cba76bfc79f1d3955f5c0ba92f660860e4ca375654bcb7c8b8570c5/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d6730352e706e67)](https://camo.githubusercontent.com/cd166e549cba76bfc79f1d3955f5c0ba92f660860e4ca375654bcb7c8b8570c5/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d6730352e706e67)

Write a function drawHTree that constructs an H-tree,
given its center (x and y coordinates), a starting length, and depth.
Assume that the starting line is parallel to the X-axis.

Use the function drawLine provided to implement your
algorithm. In a production code, a drawLine function would render a real
 line between two points. However, this is not a real production
environment, so to make things easier, implement drawLine such that it
simply prints its arguments (the print format is left to your
discretion).

Analyze the time and space complexity of your algorithm.
In your analysis, assume that drawLine's time and space complexities are
 constant, i.e. O(1).

Constraints:

* [time limit] 5000ms
* [input] double x
* [input] double y
* [input] double length
* [input] double depth
  * 0 ≤ depth ≤ 10
