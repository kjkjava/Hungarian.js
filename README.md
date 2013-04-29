Hungarian.js
============

A JavaScript implementation of the Hungarian algorithm.

About This
----------
The Hungarian algorithm is used to optimize pairings between two sets, when each pairing has an associated cost.  The problem is knonw as the "assignment problem," and is typically represented as a matrix of costs or a weighted bipartite graph.  [Wikipedia](http://en.wikipedia.org/wiki/Hungarian_algorithm) goes into more detail on both the Hungarian algorithm and the assignment problem.

Hungarian.js is a JavaScript implementation of the algorithm.  This implementation assumes all positive numbers in the input.  A "forbidden value" is used in the code and it must be larger than or smaller than all other inputs.

Usage: `hungarian(matrix, [isProfitMatrix=false], [returnSum=false])`
