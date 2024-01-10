## Building a Cell and Anatomy Ontology of C.elegans
*Raymond Y. N. Lee and Paul W. Sternberg*

*Published Dec 2002 https://doi.org/10.1002/cfg.248*

# Abstract
Cell-based information concerning gene expression and the role of specific cells in developmental signalling and behavioural circuits

WormBase has begun to construct a C.elegans cell and anatomy ontology

# Introduction
Ontologies (e.g. GO) give a logical machine readable structure for large scale genomic analysis

# CECAO
No. of cells at all times in a life cycle

Near precise knowledge of most cell’s lineage and developmental fates

A few cases of the nature of developmental indeterminacy

EM level how most neurons are connected to each other

https://royalsocietypublishing.org/doi/10.1098/rstb.1976.0085
https://royalsocietypublishing.org/doi/10.1098/rstb.1986.0056

Functions of many cells in development or in mature animals

Detailed functional and morphological information on anatomy

# C.elegans cells and anatomy
Free living soil nematode that feeds on bacteria in the laboratory

Two sexes: self-fertilising hermaphrodite (morphologically female) and male

7 major development stages: embryo, 4 larval stages (L1-L4) reproductive adult, dispersal dauer larval stage (alternative to L3): only takes place under certain harsh living 
conditions

C.elegans has a general body plan: 2 concentric tubes separated by a pseudocoelom

Neurons make contacts en passant and the major nerve bundles form the circumpharyngeal nerve ring and the dorsal and ventral cord (The Nematode Caenorhabditis elegans)

Reconstruction of the entire nervous system from EM by White et al which provides an anatomical sketch of how neurons are connected to each other, to muscle and to other postsynaptic partner cells

Based on the anatomical analyses, neurons are grouped into classes, such that members of each class share similar anatomy and thus may also perform similar functions

# Design of CECAO
Objective of CECAO is to provide an ontology that contains all the information about the C.elegans cell and anatomy so that the information can be parsed by computer programs

Ontology of controlled vocabularies that readily supports annotation of experimental results, such that the outcomes can be queried effectively

Ontology considers: cell lineage, position, cell type, organ and function

Complex nature of the range of information -> a directed acyclic graph to represent the data

# Distinction between a cell and its nucleus

Lineage: determined by observation with Nomarski optic primarily concerns nuclei. Nucleus divides to give rise to 2 nuclei, whereas the identity of a cell is often established by a set of properties, a nucleus has a defined parentage and thus a precise position in a lineage. CECAO is used to define nodes in lineages. Child nucleus has a DESCENDENT_OF relationship with the parent nucleus.

Syncytia: product of cell fusions or incomplete cell divisions that result in a cell with multiple nuclei. CECAO, for each nucleus we define a node and it has a PART_OF relationship with teh syncytium that contains it.

# Sexual dimorphism
Two new relationships: DESC_MALE and DESC_HERM to encode sex-specific differences

# Indeterminacy
Create a node to represent the indeterminate state of use a DEVELOPS_FROM relationship

For example, P1/P2 and include 4 statements:

P1/P2 DEVELOPS_FROM AB.plapaapp

P1/P2 DEVELOPS_FROM AB.prpppaaaa

P1 DEVELOPS_FROM P1/P2

P2 DEVELOPS_FROM P1/P2

# Current progress and future plans
Imported sets of data from available resources

Anatace: Sylvia Martinelli

“Parts list”: Leon Avery

5000 nodes, ⅓ have definitions (complete number of nodes is unknown)

3000 cell and 500 cel group terms in WormBase

80 separate lineage trees with a total of 6000 nodes

CECAO needs to reconcile 15 000 relationships, assuming that each cell ,on average, has 5 edges

CECAO is currently lacking comparative anatomy and therefore collaborating with WormAtlas
Provide an online encyclopaedia of C.elegans cells and anatomy to construct CECAO with a top-down approach
