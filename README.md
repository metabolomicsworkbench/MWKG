# MWKG
Metabolomics Workbench Knowledge Graph (MWKG)

MWKG is a Neo4j-based graph database for the metadata associated with the metabolomics data available at the <a href="https://www.metabolomicsworkbench.org/">Metabolomics Workbench (MW)</a>, also known as the National Metabolomics Data Repository (NMDR). 

MWKG can be used to retrieve a specific study/project and explore its data, retrieve studies associated with a Condition (disease/phenotype/treatment) or a Sample/Species/Analytical method and perform Analytics such as centrality detection (Degree/Eigenvector/PageRank), community detection (Louvain/Label propagation) and finding common link between entities (Shortest Path). MWKG is based on <a href="https://neo4j.com/">Neo4j<a>, uses <a href="https://neo4j.com/docs/bloom-user-guide/current/about-bloom/">Bloom</a> for visualization and is current hosted on a local linux desktop. It will be ported to a publicaly available server in the near future. <a href="https://docs.google.com/presentation/d/1V7QJ38sajHVyc-uvqJPUQeYIE1ys0spq8vG5C8OgqRM/edit#slide=id.g27f5ee4e5ae_0_0">MWKG tutorial</a> provides an overview.
