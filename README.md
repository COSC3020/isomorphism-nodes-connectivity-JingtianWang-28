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

Assuming that the number of nodes in graph A and graph B is the same, n, and there must be an edge between every two nodes, then the structure of their edges will be consistent no matter how they are arranged.

Because graphs G1 and G2 have the same number of nodes n, we can construct a bijection f from G1 nodes to G2 nodes: va -> vb

|VA| = |VB| = n, then bijection f: VA -> VB 

Any two different nodes (u,v)∈Va in G1 will have an edge (u,v)∈Ea

for any u,v ∈ VA, (u,v) ∈EA <-> (f(u),F(v)∈EB)

f is a bijection and preserves the edge structure, so it is isomorphic as long as the number of nodes is the same.

There must be edges between all pairs of nodes in the graph, and bijection can ensure the correspondence between nodes and edges.

###

source：https://en.wikipedia.org/wiki/Isomorphism https://www.geeksforgeeks.org/graph-isomorphisms-connectivity/#what-is-graph-isomorphism https://en.wikipedia.org/wiki/Bijection

Plagiarism Statement: “I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice
