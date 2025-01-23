# Complexity

As software size increases, complexity increases exponentially.

Complexity is related to the number of interactions between lines of code.

Using graph theory we can say that a line of code is a node, and the relationship between one line of code to another line of code is an edge.

If we say that program is a series of lines of code, and each line of code is related to every other line of code, then we have a complete graph.

A complete graph is a graph where every node is connected with every other node.

| node / line of code | edge / complexity |     |
| ------------------- | ----------------- | --- |
| 1                   | 0                 |     |
| 2                   | 1                 |     |
| 3                   | 3                 |     |
| 4                   | 6                 |     |
| 5                   | 10                |     |
| 6                   | 15                |     |
| n                   | n(n-1)/2          |     |

## Moore's Law
The density of transistors on a chip will double every two or so years.
This law has held up pretty well over the years
Corollaries
- RAM size in a computer
- Hard drive Space in a computer
- Internet Bandwidth

## Complexity Trend
Maximum number of lines of code, n, grows geometrically, n = 2<sup>5</sup>
Maximum number of interconnections between lines of code grows exponentially n(n-1)/2

