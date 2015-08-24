% The Metastructure Model
% Zachary King; Ali Ebrahim
% August 19, 2015

# What is a metastructure model?

A metastructure model is:

- A genomic knowledge base
- A collection of genome-oriented annotations that include:
    - Genes
    - Transcription units (TU)
    - Transcription start sites (TSS)
    - Ribosome binding sites (RBS)
    - (Translation pause sites)
    - Sigma factor binding sites
    - Transcription factor binding sites
- A self-consistent representation of the genome with rules for consistency

The Metastructure model includes the content of a traditional genome annotation,
but it has a different purpose. Eventually, the Metastructure model should
include all the knowledge about a genome that has positional information.

Experimental error is considered in the model by assigning a confidence interval
for each locus in the model.

A Metastructure model is constructed using a reference genome annotation and
omics datasets. A workflow can be described for this process. It includes a
number of manual and automated steps.

*Rules for consistency* are defined. These rules identify groups of features
whose locations are not consistent with our general understanding of the
genome. The inconsistencies identified by these rules require manual
curation. They lead to improvements in the model and improvements in our
understanding of genome structure and organization.

# From genome annotation to metastructure

Genome annotations were the first product of the sequencing era. Early
annotations, such as the genome annotation for *E.\ coli* [@Blattner1997],
included genes, operons, regulatory sites, mobile genetic elements, and
repetitive sequences in the genome.

Originally, features were identified at the genome scale using "sensors" that
scanned for hallmark signals of a feature like a transcription start site
or using sequence homology with genes that had already been
annotated by more tedious means [@Stein2001].

The SEED project promotes an approach to genome annotation that is based on
*subsytems* [@Overbeek2005].

The NCBI RefSeq database houses genome annotations, and NCBI has a genome
annotation pipeline to generate annotations for new genome
sequences [@Pruitt2012].

To build upon genome annotations---which have been referred to as *one
dimensional*---it is possible to build genome-scale models (GEMs) of metabolic
pathways and their constituent biochemical reactions, reactants, and genes. GEMs
are a second dimension of annotation [@Reed2006]. Beyond just annotation, GEMs
provide a mathematical structure and can actually predict biological phenotypes
[@Bordbar2014]. Therefore, they can be improved by comparing model predictions
to experimental observations and then systematically addressing the failed
predictions [@Bordbar2014; @Reed2006].

(@Reed2006 also brings up the spatial localization of genomes, calling it 3D
annotation or ultrastructure. Is this part of the metastructure model? Figure\ 1
in that paper is pretty strange.)

Mathematical models of the genome do not yet exist. We propose a mathematically
structured model of the genome: a *metastructure model*.

# Notes

- the term "metastructure" has been used for proteins
  [10.1007/s00018-009-0117-0], but it was also discussed with the current
  meaning in SB1 [1107038855]
- other references: @Aziz2008, @Cho2009, @Mendoza-Vargas2009, @Cho2012,
  @Harrow2012, @Salgado2013, @Karolchik2014

# References
