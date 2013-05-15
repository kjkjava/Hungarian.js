Hungarian.js
============

A JavaScript implementation of the Hungarian algorithm.

About This
----------
The Hungarian algorithm is used to optimize the pairing of items between two sets, where each pairing has an associated cost.  The problem is known as the "assignment problem," and is typically represented as a matrix of costs or a weighted bipartite graph.  [Wikipedia](http://en.wikipedia.org/wiki/Hungarian_algorithm) goes into more detail on both the Hungarian algorithm and the assignment problem.

Hungarian.js is a JavaScript implementation of the algorithm.

Usage: `hungarian(matrix, [isProfitMatrix=false], [returnSum=false])`

Credits
-------
This code was ported from the Java implementation at https://github.com/w01fe/hungarian/blob/master/src/jvm/w01fe/hungarian/HungarianAlgorithm.java which was originally from http://konstantinosnedas.com/dev/soft/munkres.htm (by Konstantinos A. Nedas).

It wasn't hard because Java and JavaScript are the same thing (jokes).  But really, it's very similar to the original.  I suppose it's not common to see O(n^3) algorithms written in JavaScript, but the future is now!
