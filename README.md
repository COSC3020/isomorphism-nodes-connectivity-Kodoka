# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## My Proof

That is to say one graph must have comparable form and relations to another if
they have the same number nodes and are completely connected. For example, take
the following two graphs:  
![Screenshot_20250419_120633_Samsung Notes](https://github.com/user-attachments/assets/dd2644b7-a909-4241-994c-665e9226d175)
The left graph, graph A, has three nodes: a, b, c. Every pair of nodes has
corresponding edges. The right graph, graph B, has three nodes: x, y, z. Again,
every pair of nodes has a corresponding edge. Due to each graph featuring the
same connections, that is every unique pair of nodes having an edge, and each
graph having the same number of nodes, we can relable nodes in graph A to match
those in graph B, and make the corresponding lable adjustments to edges to
demonstrate these two graphs are isomorphic.  

Let $G_1 = (V_1, E_1)$ and $G_2 = (V_2, E_2)$ be two different graphs where the
number of nodes in the graphs, $n$, $= |V_1| = |V_2|$. $G_1$ and $G_2$ are both
complete graphs, meaning every unique pair of nodes in each graph has a
connecting edge.  

As $n = |V_1| = |V_2|$ we have a bijection by assigning a
unique node in $V_1$ to each node in $V_2$, $f(V_1) \implies V_2$.  
Since both graphs are complete, for every unique pair of nodes $(u, v) \in V_1$,
there exists an edge $(u, v) \in E_1$. As $f$ is bijective, a comparable pair of
unique nodes, $(f(u), f(v))$ in $V_2$ must also exist, as well as a corresponding
$(f(u), f(v))$ in $E_2$, as $G_2$ is also complete.  

Thus, for all $u, v \in V_1$ where $u \neq v: (u, v) \in E_1 \Longleftrightarrow
(f(u), f(v)) \in E_2$

## Sources

I took Discrete Mathematics as a distance learning class through UND, and
distinctly remember having to answer almost this exact same question; however,
access to old submissions is lost 30 days after completing the course, so I don't
acutally have access to my submission.

## Plagiarism Notice

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
