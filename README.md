# CodeTree
Fast Subgraph Search with Graph Code Indices

## Usages:
Before executing the subgraph search commands, please download VEQ_S from [this link](https://github.com/SNUCSE-CTA/VEQ)

Indexing of a Graph Database<br>
java -jar ac.kwansei.codetree.jar -i [data graph file]

Subgraph Search with Code Tree<br>
java -jar ac.kwansei.codetree.jar [serialized file] [data graph file] [query graph directory]


## Example Usages:
Indexing of a Graph Database<br>
java -jar ac.kwansei.codetree.jar -i AIDS.gfu

Subgraph Search with Code Tree<br>
java -jar ac.kwansei.codetree.jar AIDS codetree.ser AIDS.gfu Query/AIDS/randomwalk/4

## Input
#[Graph ID]<br>
[Number of Vertices (n)]<br>
[Label of Vertex v_1]<br>
...<br>
[Label of Vertex v_n]<br>
[Number of Edges (m)]<br>
[Vertex ID of Edge e_1] [Vertex ID of Edge e_1]<br>
...<br>
[Vertex ID of Edge e_m] [Vertex ID of Edge e_m]<br>



