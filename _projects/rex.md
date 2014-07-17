---
layout: project
title: Retrieval of Experiments
permalink: /projects/rex/
status: completed
standfirst: Probabilistic retrieval and visualization of biologically relevant microarray experiments from large collections of gene expression studies.
---

As ArrayExpress and other repositories of genome-wide experiments are reaching a mature size, it is becoming more meaningful to search for related experiments, given a particular study. The goal of this project is to introduce methods that allow for the search to be based upon measurement data, rather than the annotation data, which usually does not contain a description of the experimental results. The goal is to retrieve experiments in which the same or very similar biological processes are activated. This can be due either to experiments targeting the same biological question, or to as yet unknown relationships.

We use Gene Set Enrichment Analysis (GSEA) and probabilistic machine learning techniques such as Latent Dirichlet Allocation (LDA) to extract information about the biological processes that are differentially activated in each experiment, to retrieve earlier experiments where the same processes are activated and to visualize and interpret the retrieval results. Results can be interpreted in terms of biological processes using the visualization techniques. Case studies on a subset of ArrayExpress show that, with a sufficient amount of data, our method indeed finds experiments relevant to particular biological questions.

_This project was a collaboration with Jose Caldas, Ali Faisal and Samuel Kaski at the Aalto University School of Science and Technology in Helsinki, Finland._