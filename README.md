This project is developping for studying exmaples of a cetain kind of associative algebras, called graph magma algebras in litterature. These algberas are basically magma algebras, where the magma structure is based on a 
simple directed graph. The file graphMagmaAlgebras.ipynb contains two classes: graphMagma for magmas induced by simple directed graphs and graphMagmaAlg for magma algebras. 

An object of type graphMagma should contain information on its underlying graph stored in graphMagma.graph. The graph is given as a list of pairs, which represent the connected components of the graph. These pairs consist of a char as 
'K' or 'N' to indicate a coplete of a null graph, respectively, and the number of the vertices in each subgraph. For example the direct sum graph $K_2\oplus N_3$ is defined by the list [('K',2),('N',3)].
other attributes like generators (graphMagma.generators), incidence matrix (graphMagma.Inc), and the multiplication table (graphMagma.multiplication_table) become ready for use. These are mainly used in creation of a graphMagmaAlg object.

In the class graphMagmaAlg, 
