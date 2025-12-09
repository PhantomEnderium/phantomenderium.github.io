# Add Discrete Math Cheatsheet to site

## Walks, Trails, Paths, Circuits
- Graph basics
    - Vertex, Edges
    - Vertex "degree" is how many edges are attached to vertex
    - Even and odd degrees, 3 edges to vertex is odd, 2 is even, etc.
- Add Walk, Trail, Path, and Circuit Information
    - Include Closed Walk and Simple Circuit
- Euler's Circuit
    - All edges must be used exactly once
    - Possible if every vertex has an even degree
    - Circuit rules, so has to start and end at the same vertex
- Euler's Trail
    - Similar deal, vertex does NOT to start and end
    - Possible if exactly 0 or 2 verticies have an odd degree
        - If 0, is a trail anywhere in an existing Euler Circuit
        - If 2, must be the start and end points.
- Hamiltonian Circuit
    - Visits every vertex once, and returns to the start

- Graph Complement
    - Take graph with edges
    - Invert edges
        - If edge between verticies, remove it
        - If no edge, add one


## Graph Matrix
- Matrix visualization of graphs
    - Each row is a vertix start
    - Each column is a vertix end
    - $\begin{bmatrix} 0 & 1 & 0 \\ 1 & 0 & 1 \\ 0 & 1 & 0 \end{bmatrix}$
- Products
    - Row A x Column B

## Isomorphic Graphs
- Looks different, same connections

## Trees
- Special kind of graph


- Two key properties
    - Connected – There is a path between any two vertices.
    - Acyclic – There are no cycles, meaning you can’t start at a vertex, follow edges, and come back to the same vertex without retracing your steps.
- Terminology
    - Root: Often, one vertex is designated as the starting point.
    - Parent / Child: In rooted trees, edges go from a parent node to child nodes.
    - Leaf: A node with no children.
    - Internal node: A node that is not a leaf; it has at least one child.
    
    - Internal Vertex - 2 or more connections
    - Terminal Vertex - 1 connection

- A tree with n vertices has exactly n−1 edges. This is because adding any more edges would create a cycle.
- There is exactly one path between any two vertices in a tree.
- Root vs Unroot
    - Rooted tree: One node is chosen as the root, and directions are implied from parent → child. Great for things like family trees or decision trees.
    - Unrooted tree: No designated root; just a connected, acyclic graph. Think of a molecular structure in chemistry.
- Binary trees (a very common type)
    - Each node has at most two children, usually called left and right.
    - Used heavily in computer science for search, sorting, and hierarchical structures.
    - Full: Every node has 0 or 2 children, so cannot have a parent with 1 child

### Binary Search Trees
- Rule: For each node:
    - All keys in the left subtree < node key
    - All keys in the right subtree > node key