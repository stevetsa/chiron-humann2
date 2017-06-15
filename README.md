# chiron-humann2
https://github.com/stevetsa/Chiron

http://huttenhower.sph.harvard.edu/humann2
HUMAnN2 is the next generation of HUMAnN (HMP Unified Metabolic Analysis Network).

HUMAnN is a pipeline for efficiently and accurately profiling the presence/absence and abundance of microbial pathways in a community from metagenomic or metatranscriptomic sequencing data (typically millions of short DNA/RNA reads). This process, referred to as functional profiling, aims to describe the metabolic potential of a microbial community and its members. More generally, functional profiling answers the question "What are the microbes in my community-of-interest doing (or capable of doing)?"

HUMAnN2 Features

Community functional profiles stratified by known and unclassified organisms
MetaPhlAn2 and ChocoPhlAn pangenome database are used to facilitate fast, accurate, and organism-specific functional profiling
Organisms included are Archaea, Bacteria, Eukaryotes, and Viruses
Considerably expanded databases of genomes, genes, and pathways
UniRef database provides gene family definitions
MetaCyc provides pathway definitions by gene family
MinPath is run to identify the set of minimum pathways
A simple user interface (single command driven flow)
The user only needs to provide a quality-controlled metagenome or metatranscriptome
Accelerated mapping of reads to reference databases (including run-time generated databases tailored to the input)
Bowtie2 is run for accelerated nucleotide-level searches
Diamond is run for accelerated translated searches
