# networks and graphs as results of sampling graphs from datasets, running 0tempIsing algorithm 
Set of graphs constructed from the synthetic datasets before and after using algorithm (in repository 0tempIsing) using graph visualization tool - Graphviz.

Notes:
1.The type of synthetic data considered for which the visualizations are shown are Checkers, Stripes, Concentric Circles and Square images. 
2.Where mentioned, CompressedGraph* refers to the PQ graph constructed due to the deterministic approximation of the 0tempIsing algorithm as in the NIPS paper.
The labels of the unknown vertices are predicted on the PQ graphs. PQ graph is the multigraph of supervertices (one vertex where similar labelled vertices have collapsed)
Collapsing happens according to the 0tempIsing algorithm on our NIPS paper.
3. Where indicated the name CompressedGraph4135* indicates for example trial 4 with 135 super-vertices.
4. MinDestruction is the alternative heurestics to predict not via longest path but via the label that causes maximum destruction of edges of PQ graph or maximum destruction of vertices upon a mistake in labelling the queried vertex.

Graph formats;
Comma Separated Files -> Script (CsvToDot in repository scripts) -> .dot -> GraphViz

Dependency:
GraphViz
