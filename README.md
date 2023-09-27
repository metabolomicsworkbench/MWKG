# MWKG
Metabolomics Workbench Knowledge Graph (MWKG).

MWKG is a Neo4j graph database for the metadata associated with the metabolomics studies available at the <a href="https://www.metabolomicsworkbench.org/">Metabolomics Workbench (MW)</a>, also known as the National Metabolomics Data Repository (NMDR). 

MWKG can be used to retrieve a specific study/project and explore its data, discover and retrieve studies associated with a Condition (disease/phenotype/perturbation) or a Sample/Species/Analytical method and perform Analytics such as centrality detection (Degree/Eigenvector/PageRank), community detection (Louvain/Label propagation) and finding a common link between entities (Shortest Path). MWKG is based on <a href="https://neo4j.com/">Neo4j<a>, uses <a href="https://neo4j.com/docs/bloom-user-guide/current/about-bloom/">Bloom</a> for visualization and is currently hosted on a local Linux desktop. It will be ported to a publicly available server soon. <a href="https://docs.google.com/presentation/d/1bsENSYiVloN_Jl_Msx9HW63VR7jJFCHKPUjoDLld66g/edit#slide=id.g284c09b2d90_0_0">MWKG tutorial</a> provides an overview.
