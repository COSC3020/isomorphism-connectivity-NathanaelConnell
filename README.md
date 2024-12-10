# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

If two graphs G(sub1) = (V(sub1), E(sub1)) and G(sub2) = (V(sub2), E(sub2)) are isomorphic it means there exists a bijection f : V(sub1) → V(sub2) such that (u, v) ∈ E(sub1) if and only if (f(u), f(v)) ∈ E(sub2).  This property of isomorphism only requires that the edge relationships in G(sub1) are preserved in G(sub2) under the mapping f.  It does not require either grpah to be complety connected.  For example, consider two graphs G(sub1) and G(sub2) with three vertices each, where G(sub1) gas edges E(sub1) = {(1,2), (2,3)} and G(sub2) has edges E(sub2) = {(a,b), (b,c)}.  The bijection f mapping 1 → a, 2 → b, and 3 → c preserces the edge relationships, so G(sub1) and G(sub2) are isomorphic, even though neither is completly connected.  
"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."
