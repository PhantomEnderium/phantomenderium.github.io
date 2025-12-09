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