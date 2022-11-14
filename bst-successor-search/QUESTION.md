# *BST Successor Search*

In a Binary Search Tree (BST), an Inorder Successor of a
node is defined as the node with the smallest key greater than the key
of the input node (see examples below). Given a node inputNode in a BST,
 you’re asked to write a function findInOrderSuccessor that returns the
Inorder Successor of inputNode. If inputNode has no Inorder Successor,
return null.

Explain your solution and analyze its time and space complexities.

[![](https://camo.githubusercontent.com/37cdc02be924aa0e6b5085c64a35d6370db75967a20f33c0e0d49d27a252afc5/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d675f30322e706e67)](https://camo.githubusercontent.com/37cdc02be924aa0e6b5085c64a35d6370db75967a20f33c0e0d49d27a252afc5/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d675f30322e706e67)

In this diagram, the inorder successor of 9 is 11 and the inorder successor of 14 is 20.

Example:
In the diagram above, for inputNode whose key = 11

Your function would return:
The Inorder Successor node whose key = 12

Constraints:

* [time limit] 5000ms
* [input] Node inputNode
* [output] Node
