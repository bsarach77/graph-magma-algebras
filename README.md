This is a math project focusing on a topic in the branch of abstract algebra. Many useful results follow from enough number of experiments through examples. With this insight, we develop this project to study examples of a cetain kind of associative algebras, called graph magma algebras in the litterature. These algberas are basically magma algebras, where the magma structure is based on a 
simple directed graph. The file graphMagmaAlgebras.ipynb contains two classes: graphMagma for magmas induced by simple directed graphs and graphMagmaAlg for magma algebras. 

An object of type graphMagma should contain information on its underlying graph stored in graphMagma.graph. The graph is given as a list of pairs, which represent the direct sum components of the graph. These pairs consist of a char as 
'K' or 'N' to specify the type of the connected component as complete or null, respectively, and the number of the vertices in each component. For example, the graph $K_2\oplus N_3$ with direct sum components $K_2$ and $N_3$ is defined by the list [('K',2),('N',3)].
Other attributes like generators (graphMagma.generators), incidence matrix (graphMagma.Inc), and the multiplication table (graphMagma.multiplication_table) are ready for use. These are mainly used in creation of a graphMagmaAlg object.

In the class graphMagmaAlg, 
