# *Matrix Spiral Copy*

Given a 2D array (matrix) inputMatrix of integers, create a
 function spiralCopy that copies inputMatrix’s values into a 1D array in
 a spiral order, clockwise. Your function then should return that array.
 Analyze the time and space complexities of your solution.

Example:

```js
input:  inputMatrix  = [ [1,    2,   3,  4,    5],
                         [6,    7,   8,  9,   10],
                         [11,  12,  13,  14,  15],
                         [16,  17,  18,  19,  20] ]

output: [1, 2, 3, 4, 5, 10, 15, 20, 19, 18, 17, 16, 11, 6, 7, 8, 9, 14, 13, 12]
```

See the illustration below to understand better what a clockwise spiral order looks like.
[![](https://camo.githubusercontent.com/4fecf20ea2bb43f008f3144924eaa65bf7306d9fc4f1df9c2b9c5b9779207e98/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d6730362e706e67)](https://camo.githubusercontent.com/4fecf20ea2bb43f008f3144924eaa65bf7306d9fc4f1df9c2b9c5b9779207e98/68747470733a2f2f7777772e7072616d702e636f6d2f696d672f636f6e74656e742f696d6730362e706e67)

Constraints:

* [time limit] 5000ms
* [input] array.array.integer inputMatrix
  * 1 ≤ inputMatrix[0].length ≤ 100
  * 1 ≤ inputMatrix.length ≤ 100
* [output] array.integer
