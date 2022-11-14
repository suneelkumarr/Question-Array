# *Largest Smaller BST Key*

Given a root of a Binary Search Tree (BST) and a number
num, implement an efficient function findLargestSmallerKey that finds
the largest key in the tree that is smaller than num. If such a number
doesn’t exist, return -1. Assume that all keys in the tree are
nonnegative.

Analyze the time and space complexities of your solution.

For example:
For num = 17 and the binary search tree below:

[![](https://camo.githubusercontent.com/37cdc02be924aa0e6b5085c64a35d6370db75967a20f33c0e0d49d27a252afc5/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d675f30322e706e67)](https://camo.githubusercontent.com/37cdc02be924aa0e6b5085c64a35d6370db75967a20f33c0e0d49d27a252afc5/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d675f30322e706e67)

Your function would return:

14 since it’s the largest key in the tree that is still smaller than 17.

Constraints:

* [time limit] 5000ms
* [input] **Node** rootNode
* [output] integer
