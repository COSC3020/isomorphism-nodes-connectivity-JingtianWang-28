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

Graph A and graph B have the same number of nodes and are fully connected, so they are isomorphic

Since A and B have the same number of vertices, let the vertex set be Va = Vb = {v1,v2...vn}

Since A is fully connected, there must be an edge connecting any two different vertices Vx Vy in Va

Since B is fully connected, there must be an edge connecting any two different vertices Vx Vy in Vb

let f:v1 -> v2, define as f(vx) = vx, for all x∈{1...n}

f is a bijection, because each vertex in Va can be mapped one-to-one to a vertex in Vb, and the same for graph B, so we have satisfied the conditions for isomorphism.

So they must isomorphic

###

source：https://en.wikipedia.org/wiki/Isomorphism https://www.geeksforgeeks.org/graph-isomorphisms-connectivity/#what-is-graph-isomorphism https://en.wikipedia.org/wiki/Bijection

Plagiarism Statement: “I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice
