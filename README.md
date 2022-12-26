# S24E
#### Video Demo:  <>
#### Description: A mathematical game about Eulerian Paths in even convex polygons diagonals

S24E is a mathematical game about Eulerian Paths in even convex polygons diagonals. It was inspired by trying to compute and express all diagonals of a convex polygon without generating repetitions.

To make the story short, the formula for the number of diagonals in convex polygons is derived from the combination formula, all diagonals are a subset of all possible combinations of from n take two. It’s possible to generate only the subset of all diagonals without generating all combinations. However, I still wasn’t satisfied with this solution because there are numbers repeating in the result, if we could link these numbers all diagonals would be more compactly expressed as sequences of numbers.

To reach these sequences of numbers, diagonals of convex polygons can also be thought as paths, one polygon has multiple paths and all paths of a polygon covers all of its diagonals. The task of finding all diagonals this way, is the task of generating the paths and connecting them, reaching directly the compact sequences of numbers that express all diagonals.

The special paths that pass through all diagonals are called Eulerian Paths: paths in a finite graph that visits every edge exactly once, allowing for revisiting vertices. For the existence of Eulerian Paths, it's necessary that zero or two vertices of the graph have an odd degree. On polygons edges are diagonals, the degree of a vertex is the number of diagonals leaving it, sides don't count.

All odd convex polygons have even degree vertices, so the shortest paths through all its diagonals have the same size as the number of diagonals. All even convex polygons have odd degree vertices, to find the shortest paths through all of its diagonals is necessary to repeat some diagonals in a way that makes all except the start and end vertices of the path of even degree.

S24E is about finding the shortest paths through all diagonals of even convex polygons. It runs offline in any browser (except some links to Wikipedia). In the game, vertices are islands and diagonals are bridges. There's a Tutorial screen explaining the interface and controls. There's Building Bridges Mode, where you build bridges freely as you find paths. There's Destroying Bridges Mode, where you select the island to end your path and the bridges to be crossed twice before trying to find paths, destroying bridges as you cross them.

Download S24E.html and open in browser.
Have fun finding your paths in life!