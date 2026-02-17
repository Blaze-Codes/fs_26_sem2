---
title: Connectivity
---
For connectivity, we only deal with undirected graphs!

# k-connected Graphs
## Definition
A graph is k-connected if one has to remove at least $k$ vertices, to disconnect two arbitrary vertices $u,v$.
## Conditions
* $|V| \geq k +1$
* For every vertices $u,v$, there always exists a path u -> v after removing up to k-1 vertices.
* For every vertex $v$, $deg(v) \geq k$, otherwise the graph is not k-connected
## Furthermore
k-connected $\implies$ (k-1)-connected, for all k > 1

## Definition Internally Vertex-Disjoint Paths
Two paths are internally vertex-disjoint, if they have no common vertex except the start and end vertex.

## Definition Edge-Disjoint Paths
Two paths are edge-disjoint if they have no common edge, they may, however, share vertices.

## Menger's Theorem (Vertex Version)
k internally vertex-disjoint paths $\iff$ graph is k-connected

## Menger's Theorem (Edge Version)
k edge-disjoint paths $\iff$ graph is k-connected

## Relationship between Connectivity Measures
vertex connectivity $\leq$ edge connectivity $\leq$ minimum degree of a graph

# For k = 1 (i.e. "normal" connected graphs)

## Cut Vertex
A cut vertex is a vertex whose removal from the graph along with it's incident edges disconnects the graph. In a tree, for example, every vertex that is not a leaf, is a cut vertex.
## Cut Edge
A cut edge is an edge whose removal leaves the graph disconnected.
## Bridge
An edge e = {u,v} is called a bridge if deg(u) = 1 or e is a cut edge (analogous for v)