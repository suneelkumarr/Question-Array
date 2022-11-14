# *Island Count*

Given a 2D array binaryMatrix of 0s and 1s, implement a
function getNumberOfIslands that returns the number of islands of 1s in
binaryMatrix.

An island is defined as a group of adjacent values that
are all 1s. A cell in binaryMatrix is considered adjacent to another
cell if they are next to each either on the same row or column. Note
that two values of 1 are not part of the same island if they’re sharing
only a mutual “corner” (i.e. they are diagonally neighbors).

Explain and code the most efficient solution possible and analyze its time and space complexities.

Example:

```js
input:  binaryMatrix = [ [0,    1,    0,    1,    0],
                         [0,    0,    1,    1,    1],
                         [1,    0,    0,    1,    0],
                         [0,    1,    1,    0,    0],
                         [1,    0,    1,    0,    1] ]

output: 6 // since this is the number of islands in binaryMatrix.
          // See all 6 islands color-coded below.
```

[![](https://camo.githubusercontent.com/45a7719af2dc8f9d53d5acce687af0fa071dd285992b738f5455a6c9c45ceae6/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d6730392e706e67)](https://camo.githubusercontent.com/45a7719af2dc8f9d53d5acce687af0fa071dd285992b738f5455a6c9c45ceae6/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d6730392e706e67)

Constraints:

* [time limit] 5000ms
* [input] array.array.int binaryMatrix
  * 1 ≤ binaryMatrix.length ≤ 100
  * 1 ≤ binaryMatrix[i].length ≤ 100
* [output] integer
