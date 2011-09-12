ualgebra.js is a tiny javascript linear algebra library.
It contains numerical implementations of basic matric operations.

Keep in mind that this this contains only numerical implementations. There's not type checking of any kind nor suport for rational numbers.

Usage
=====

The functions accept matrices as two dimentional arrays. A matrix is represented as an array of lines, a line is simply an array.

examples

```javascript
M = [[1,2],[3,4]];

//transpose
T = transposeMatrix(M); //returns [[1,3],[2,4]]

//inverse
inverseMatrix(M); // return [[-2,-1],[-1.5,-0.5]]


//determinant
determinant(M) //returns -2


```