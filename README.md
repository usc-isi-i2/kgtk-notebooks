# KGTK Notebooks

**Welcome to the KGTK notebook tutorial!**

The goal of this tutorial repository is to introduce the functionality of KGTK to first-time users. The [Knowledge Graph Toolkit (KGTK)](https://kgtk.readthedocs.io/en/latest/) is a comprehensive framework for the creation and exploitation of large hyper-relational knowledge graphs (KGs), designed for ease of use, scalability, and speed. The tutorial consists of several notebooks that demonstrate how to perform network analysis, graph profiling, knowledge enrichment, and embedding computation over a portion of the Wikidata knowledge graph. The tutorial notebooks can be found in the `tutorial` [folder](https://github.com/usc-isi-i2/kgtk-notebooks/tree/main/tutorial). All notebooks require minimum configuration and can be run locally or in Google Colab in a matter of a few minutes. The input data for the notebooks is stored in the `datasets` [folder](https://github.com/usc-isi-i2/kgtk-notebooks/tree/main/datasets). Basic understanding of knowledge graphs is sufficient for this tutorial. 

This repository has been created for the purpose of the KGTK tutorial presented at ISWC 2021. For more information on this tutorial, see our [website](https://usc-isi-i2.github.io/kgtk-tutorial-iswc-2021/).

## Notebooks

1. `kg-profiling.ipynb` performs profiling of a Wikidata subgraph, by computing deep statistics of its classes, instances, and properties.
2. `kg-graph-embeddings.ipynb` computes graph embeddings of a Wikidata subgraph using kgtk, demonstrates how to use these embeddings for similarity estimation, and visualizes them.
3. `kg-augment.ipynb` shows how structured data from IMDb can be integrated into a subset of Wikidata.
4. `enriching-wikidata-with-getty.ipynb` shows how LOD graphs like Getty Vocabulary can be used to enrich Wikidata by using kgtk operations.
5. `kg-network-analysis.ipynb` analyzes the family network of Arnold Schwarzenegger (Q2685) in Wikidata by using KGTK operations.

## Contact
* Amandeep Singh (`amandeep@isi.edu`)
* Pedro Szekely (`pszekely@isi.edu`)
* Filip Ilievski (`ilievski@isi.edu`)
