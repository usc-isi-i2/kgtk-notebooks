# Use Case Notebooks

This folder contains notebooks for that address practical use cases. These notebooks may use or crreate files greater than 10GB compressed, 
so the needed files must be loaded from the KGTK Shared Google drives. 
Contact us for access to these files.

## Bio Subgraphs
https://github.com/usc-isi-i2/kgtk-notebooks/blob/main/use-cases/bio-subgraphs.ipynb

There is a community of folks interested in technology to create subgraphs in the bio-informatics domain. 
The **bio subgraphs** use case shows how to use KGTK to create a subgraph of Wikidata containing anatomical structures,
with edges to represent has hart/part of relation. The challenge is that most anatomical structures are instances 
of subclasses of `anatomical structure (Q4936952)`, so the task is computationally demanding. 

The notebook shows how to use KGTK to create the subgraph in a few minutes, compute connected components and visualize the subgraph.


## Constructing a KG for similarity in the P279 graph
https://github.com/usc-isi-i2/kgtk-notebooks/blob/main/use-cases/p279-similarity.ipynb

In this use case we construct a subgraph of Wikidata containing all classes, defined as items that participate in the `subclass of (P279)` relation in Wikidata. 
The edges in the subgraph are all edges between two classes. The resulting graph is very sparse, as the average out-degree of classes is 1.5 (not counting P31 and P279).
The notebook explores the idea of augmenting the graph by inheriting properties defined on superclasses to the subclasses.
The notebook explores the challenges to isolate classes for common objects from the huge class hierarchies related to the bionformatics domain.
In the augmented graph, the average outdegree of classes is 68 (compared to 1.5 in the original graph)
