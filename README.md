ualgebra.js is a tiny javascript linear algebra library.
It contains numerical implementations of basic matric operations.

Keep in mind that this this contains only numerical implementations. There's not type checking of any kind nor suport for rational numbers.

Usage
=====

The functions accept matrices as two dimentional arrays. A matrix is represented as an array of lines, a line is simply an array.

examples
```javascript
M = [[1,2],[3,4]];

//tranpose
T = transposeMatrix(M);
```