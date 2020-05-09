# gfpml-datasets

## OBO

This is the basic version of the GO filtered such that the graph is guaranteed to be acyclic, and annotations can be propagated up the graph. The relations included are is_a, part_of, regulates, negatively_regulates and positively_regulates. This version excludes relationships that cross the 3 main GO hierarchies. This is the version that should be used with most GO-based annotation tools.

Release date: 2018-11-10

Downloaded from [here](http://geneontology.org/page/download-ontology).

## Genomes

This files include information about gene structure. This includes, among others, the following attributes:

+ seqname - name of the chromosome or scaffold; chromosome names can be given with or without the 'chr' prefix. Important note: the seqname must be one used within Ensembl, i.e. a standard chromosome name or an Ensembl identifier such as a scaffold ID, without any additional content such as species or assembly. See the example GFF output below.
+ source - name of the program that generated this feature, or the data source (database or project name)
+ feature - feature type name, e.g. Gene, Variation, Similarity
+ start - Start position of the feature, with sequence numbering starting at 1.
+ end - End position of the feature, with sequence numbering starting at 1.
+ strand - defined as + (forward) or - (reverse).

See [here](https://www.ensembl.org/info/website/upload/gff.html) for a more detailed description about attributes.

Release date: 09-06-18

Downloaded from [here](http://www.ensembl.org/info/about/species.html).

## GO Annotations

A GO annotation is a statement about the function of a particular gene. Each GO annotation consists of an association between a gene and a GO term. Evidence is presented in the form of a GO ‘evidence code’ and either a published reference or description of the methodology used to create the annotation.

Date Generated by GOC: 2018-10-08

GO version (OBO): 2018-09-06.

Downloaded from [here](http://www.geneontology.org/page/download-go-annotations).

## Centromeres location

For humans downloaded from [here](http://www.ensembl.org/Human/Search/Results?q=centromere;site=ensembl_all;page=1;facet_feature_type=Sequence;facet_species=Human) and for scer downloaded from ...

## LEA

This files includes LEA information for each GO term presents in each organism.

## lists.cvs

Contains every gene annotation, with non IEA evidence, for each organisms. All lists must have at least two gene annotated.

## results.csv

Contains clusterings curves for each GO term with at least two gene annotated.

## preprocessed.tar.gz

Contains processed data about genomes and annotations
