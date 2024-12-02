# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


///

G1G2 is fully connected and has the same number of nodes, then there must be an f that allows G1 to be mapped to G2. Since every node in G1 can be mapped to the corresponding unique node in G2, f is a bijection.

since G1 is fully connected , any two node a,b∈V1 are connected by egde (a,b)∈E1

so it must have f let the edge f(a),f(b)∈E2 map to corresponding node f(a),f(b)∈V2.

Since f is a bijection, f can map every unique node and edge of G1 to a unique node of G2 while preserving structural equivalence.

So f preserves the relationship from G1 to G2 and satisfies f:V1 -> V2 such that (u,v)∈E1 iff (f(u),f(v))∈E2

###

source：https://en.wikipedia.org/wiki/Isomorphism https://www.geeksforgeeks.org/graph-isomorphisms-connectivity/#what-is-graph-isomorphism https://en.wikipedia.org/wiki/Bijection

Plagiarism Statement: “I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice
