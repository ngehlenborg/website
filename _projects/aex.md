---
layout: project
title: ArrayExpress Explorer
permalink: /projects/aex/
status: completed
standfirst: An ontology-guided visual exploration tool for the ArrayExpress Archive built around a tree map visualization of a biomedical ontology.
---

The ArrayExpress Archive currently contains data from over 10,000 studies, in which several hundreds of diseases, genotypes, tissues and other experimental conditions have been analyzed. The search interface of the ArrayExpress Archive provides extensive tools to query for specific conditions based on keywords and to filter search results. However, the interface is not well suited to provide an overview of the available data sets or to browse through the content of the archive.

We have developed a web-based user interface built around a tree map visualization of the Experimental Factor Ontology (EFO) to provide an overview of the data sets in the ArrayExpress Archive and to enable ontology-guided browsing. The EFO models the relationships between experimental variables used in studies that have been deposited in ArrayExpress. We convert the EFO into a tree and for every EFO term we determine the number of studies in the ArrayExpress Archive annotated with this term. The resulting tree with node weights is visualized as a tree map, where each node is represented by a rectangle, whose size corresponds to the node weight relative to the node weights of its siblings. This construction efficiently provides an overview of the amount of data available for the different terms of the EFO and can be explored either by descending down individual branches of the EFO or by viewing the entire EFO at different depths.

Our experience with our prototype implementation shows that the visual approach is highly efficient for particular tasks and generally complements the keyword-based search interface very well. We expect that similar approaches will become increasingly important as the amount of biomedical data in public repositories continues to grow rapidly.