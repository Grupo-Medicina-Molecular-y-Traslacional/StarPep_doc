# StarPep toolbox User Guide
View the User Guide at [Grupo-Medicina-Molecular-y-Traslacional.github.io/StarPep_doc](https://Grupo-Medicina-Molecular-y-Traslacional.github.io/StarPep_doc).

## About the Project
[StarPep toolbox](http://mobiosd-hub.com/starpep/) is a software for studying the antimicrobial peptides' (AMPs) chemical space with molecular network-based representations and similarity searching models. This application aims to contribute to peptide drug repurposing, development, and optimization. 

This tool was developed as a Java desktop application that integrates the functionalities of several open-source projects. The graphical user interface was built on top of the [NetBeans Platform](https://platform.netbeans.org/), using the Java SE Runtime Environment 8. The graph database structure was implemented with the [Neo4j](https://neo4j.com/) platform. Some visualization features and the calculation of network properties were based on [Gephi](https://gephi.org/). The sequence alignment algorithms were implemented using the [BioJava](https://biojava.org/) API. 

The AMPs were collected from a large variety of biological data sources to be organized into an integrated graph database called
[starPepDB](https://doi.org/10.1093/bioinformatics/btz260), composed of 45.120 AMPs and their metadata. This integrated graph database is
embedded in StarPep toolbox to enable end-user querying, filtering, visualizing, and analyzing the AMPs taking advantage of network-based representations.

The main features of StarPep toolbox are listed below:

* **AMPs' chemical space filtering:** obtain a subset of AMPs from the StarPepDB using their metadata (function, target pathogen, biological origin, chemical modifications, original database, and cross-referenced entries to PDB, PubMed, and UniProt).

* **Molecular descriptors:** calculate molecular descriptors of the AMPs by applying statistical and aggregation operators on physicochemical amino acid properties (e.g., net charge, isoelectric point, molecular weight, etc.).

* **Network Science:** build different types of networks (metadata, chemical space, and half-space proximal) and calculate global/local properties, centrality metrics, communities, etc.

* **Similarity searching:** create multi-query similarity searching models that can lead to the repurposing of AMPs with novel functional activities.

You can find the source code of StarPep in [this GitHub repository](https://github.com/Grupo-Medicina-Molecular-y-Traslacional/StarPep).

## Acknowledgments
Special thanks to the developers of [quarto](https://quarto.org/). We deployed this site with the [quarto publish command and GitHub action alternative](https://quarto.org/docs/publishing/github-pages.html#github-action). An example of how to use this method is available in this [Github repository](https://github.com/pommevilla/friendly-dollop).
