# Dissertation-Functions
List of functions developed for the Investigation of Bacterial Genes

Developing new antibiotics requires knowledge of the role of bacterial genes. At its
simplest, bacterial genes can be classified as those that are essential for the survival of
the bacterium and those that are not. Non-essential bacterial genes are more tolerant of
genetic insertions than essential genes and therefore tend to have lower insertion densities.
Bayesian approaches have recently been developed to classify bacterial genes using gene
insertion densities but it may be possible to improve the classification performance by
incorporating other sources of genetic information.

Bacterial genomes are circular and DNA replication starts at a particular point on
this circle called the replication origin. Replication proceeds in both directions from the
replication origin around both halves of the circular DNA molecule (these halves are called
replichores). It has been hypothesised that essential genes exhibit a tendency to both form
essential gene clusters (not randomly positioned around the genome) and a preference for
residing near the replication origin.

The primary aim of this project is to develop approaches that allow testing of these two
hypotheses and to implement them on both simulated data and the three available bacterial
datasets. A secondary aim of this project is to use these additional sources of information
alongside the gene-level insertion densities to improve the classification of bacterial genes.
Dissertation Structure

Compulsory components
 Exploratory data analysis of the three bacterial datasets, with regard to the two main research
questions for all replichores.
 Propose a method to assess whether essential genes have a tendency to reside near the
replication origin.
 Simulate some basic data to investigate the effectiveness of the proposed method.
 Apply the method to the three datasets and report the results.

Optional components
 Propose a method to assessing the evidence for essential gene clustering.
 Simulate data to investigate the effectiveness of the proposed method.
 Apply the method to the three datasets and report the results.
 Consider how to use essential gene clustering and the tendency of essential genes to reside near
the replication origin alongside the gene-level insertion densities to classify bacterial genes.
Implement the proposed approaches on some of the datasets, depending on the outcomes of
the exploratory analysis.
