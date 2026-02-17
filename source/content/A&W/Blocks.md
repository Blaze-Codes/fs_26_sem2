# Definition
For the equivalence relation ~, we call each equivalence class a block. For example, for an arbitrary vertex $u$: $[u]_{\sim}$, denotes the set of all vertices that share a cycle with $u$. 
## Equivalence Relation
We define $e$  ~ $f$  $\iff$ $e = f \space \lor \exists$ a cycle containing $e$ and $f$.

The proof is left as an exercise to the reader ;)


## Intersection of Blocks
Two distinct Blocks can intersect in at most one vertex, and that vertex has to be a cut vertex. Consider the following picture:
![[Pasted image 20260217155559.png]]
(Note the obvious: Only adjacent blocks share a cut vertex)

### Why at most one?
Otherwise we can construct a cycle containing vertices from both blocks and two of the shared vertices. 

### Why a cut vertex?
With removal of the vertex, all paths in both blocks are broken, making the graph disconnected.