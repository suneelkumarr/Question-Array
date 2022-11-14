# *Sales Path*

The car manufacturer Honda holds their distribution system
 in the form of a tree (not necessarily binary). The root is the company
 itself, and every node in the tree represents a car distributor that
receives cars from the parent node and ships them to its children nodes.
 The leaf nodes are car dealerships that sell cars direct to consumers.
In addition, every node holds an integer that is the cost of shipping a
car to it.

Take for example the tree below:

[![](https://camo.githubusercontent.com/b6593c29e70ddbc421d8c1dd99e868c2cdd0364ae85439a95d76e24fb8c8df97/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d675f30312e706e67)](https://camo.githubusercontent.com/b6593c29e70ddbc421d8c1dd99e868c2cdd0364ae85439a95d76e24fb8c8df97/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d675f30312e706e67)

A path from Honda’s factory to a car dealership, which is a
 path from the root to a leaf in the tree, is called a Sales Path. The
cost of a Sales Path is the sum of the costs for every node in the path.
 For example, in the tree above one Sales Path is 0→3→0→10, and its cost
 is 13 (0+3+0+10).

Honda wishes to find the minimal Sales Path cost in its
distribution tree. Given a node rootNode, write an function
getCheapestCost that calculates the minimal Sales Path cost in the tree.

Implement your function in the most efficient manner and analyze its time and space complexities.

For example:

Given the rootNode of the tree in diagram above

Your function would return:

7 since it’s the minimal Sales Path cost (there are actually two Sales Paths in the tree whose cost is 7: 0→6→1 and 0→3→2→1→1)

Constraints:

* [time limit] 5000ms
* [input] Node rootNode
  * 0 ≤ rootNode.cost ≤ 100000
* [output] integer
