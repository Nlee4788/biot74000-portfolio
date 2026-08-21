---
permalink: /toolkit/
title: "Bioinformatics Toolkit"
author_profile: true
---

_Tools, databases, and methods catalogue I have worked with. Curated and organized by their use._


## Sequence Analysis and Data Visualization

### Geneius, file type .fasta, .fastq, plain text/.ab1 ,  .scf, Biosystems chromatograms

**Use example:** 

Molecular Biology II course, Applied Biosystems chromatogram. The analysis of kale samples vs other vegetables or fish samples.

**Strengths / Limitations:** 

Strength: 
Standard Chromatogram Format is not in-depth and compares to the company's available information 

Limitations/ Issues: 
not other databases of choice unless specialized payment

### Chromas, designed for viewing and editing chromatograms from automated DNA sequencing

**Use example:** 

Molecular Biology I course, Free software tool, plasmid and gene determination of food 

**Strengths / Limitations:** 

Strength: 
Strong with easy visuals and informative confidence pieces

Limitations/ Issues: 
Weak at the beginning and end of confidence

---

## Sequence Analysis Tool

### NCBI-BLAST (Basic Local Alignment Search Tool)

**Use example:** 
BLASTp was used to find TP53 (Human Tumour Protein 53) in a database and determine the closest known relatives of a search for alignment comparison in lecture examples. A sequence query was also compared with examples of lower annotated quality primary sources. The E-values and confidence were observed for which hits were meaningful. Used to analyze TP53 (NM_000546) and compare against nucleotide collection databases. The second use was for the biodegradation of bphA1 and checking sequence homologs. Partial success with the whole genome of the fungal organism, but the exact gene was new and couldn't be located. 

**Strengths / Limitations:** 
Strengths: 
Simple and fast locating/ identification of homologous genes, species, and conserved regions.
Limitations/ Issues: 
Similarity does not prove function. Similar sequences are shown, but the top hit by relevance score is not certain. Care is needed to avoid mix-ups

### BLASTN, type- .FASTA, Compare nucleotide sequences against nucleotide databases

**Use example:** 
Used to analyze TP53 (NM_000546) and compare against nucleotide collection databases; can also be applied to bphA1 for identifying homologs involving biodegradation

**Strengths / Limitations:** 
Strength: 
Fast identification of homologous genes, species, and conserved regions
Limitations/ Issues: 
Similarity does not prove function

### BLASTP, type .FASTA, Protein sequence similarity search

**Use example:** 
Useful for comparing AcrB efflux pump proteins associated with antimicrobial resistance

**Strengths / Limitations:** 
Strength: 
Functional predictions based on protein homology
Limitations/ Issues: 
Cannot definitively determine protein function

### BLASTX, type- . FASTA, Translates nucleotide sequence and searches protein databases

**Use example:** 
Can identify translated products of environmental biodegradation genes, such as bphA1

**Strengths / Limitations:** 
Strength: 
Identifies proteins encoded by unknown DNA sequences
Limitations/ Issues: 
Computationally intensive

### Clustal Omega, file- FASTA, Multiple sequence alignment (MSA)

**Use example:** 
Alignment of TP53 orthologs to identify conserved functional residues

**Strengths / Limitations:** 
Strength: 
Easy web interface, widely used, shows sequence conservation
Limitations/ Issues: 
Less accurate for highly divergent datasets

### (Future Practice) MUSCLE, file type-FASTA, MSA tool

**Use example:** (Future Practice)
Comparative analysis of resistant and susceptible acrB alleles

**Strengths / Limitations:** 
Strength: 
Often higher accuracy for divergent sequences
Limitations/ Issues: 
Slower than Clustal for large datasets

---

## Data Visualization (Want to try heatmaps and volcano plots for seed data, then capstone information if possible) 

### Excel

**Use example:** 
Bioinformatics, plant growth had messy flower and seed data. uses .csv file type.

**Strengths / Limitations:** 
Strength: 
Nearly all computer users know how to manage general cell operations and data organization due to the availability and ease of use of adaptable resources.
Limitations/ Issues: 
Opening the file after download, or at any time, may break RStudio's readability or interpretability for the machine software at random. Needs to remain untouched. 

### UCSC Track Visualization, file type- BED, VCF, BAM, Genomic context visualization

**Use example:** 
TP53 genomic features, ClinVar and gnomAD variant overlays

**Strengths / Limitations:** 
Strength: 
Integrates many annotation layers
Limitations/ Issues: 
Requires familiarity with tracks

### AlphaFold pLDDT Visualization, file type- PDB/mmCIF, Structural confidence mapping

**Use example:** 
Assessing confidence of NPR3 structure predictions

**Strengths / Limitations:** 
Strength: 
Quickly identifies reliable regions
Limitations/ Issues: 
Confidence does not mean correct, just similar

---

## Databases & Data Retrieval

### UniProt and Blast

**Use example:** 
Protein function of query. Searched the acrB protein sequence for an in-class activity (Bacteria antimicrobial resistance). Annotation quality assessment and example of antimicrobial resistance and multidrug efflux pumps. The first assignment tried bphA1 using (Burkholderia xenovorans- bioremediation with environmental biotech) but failed to find the protein. The Escherichia coli acrB protein/gene, associated with antimicrobial resistance and microbial genomics, was sought instead. This was easier to find due to the widespread study of E. coli. UniProtKB/Swiss-Prot, file type- FASTA, TSV, XML.

**Strengths / Limitations:** 
Strength: 
High-quality reviewed annotations of the secondary database.
Limitations/ Issues: 
Not all proteins were reviewed, and some notes recorded on paper for the pipeline have been misplaced.  

### GenBank RefSeq

**Use example:** 
Used to obtain the TP53 NM_000546 reference sequence during an in-class activity for the human tumour gene. File type- FASTA, Curated reference sequences. 

**Strengths / Limitations:** 
Strength: 
High-quality reference data. Non-redundant and easy to check relevance to search or related hits. 
Limitations/ Issues: 
Some entries are temporary, provisional, and prone to changes in version. The website changed its name, and the new version was called something else. Needs to stay current with workflow history records, alongside keeping duplicates of older versions if necessary. 

### NCBI GenBank, file type- FASTA, GenBank, Primary archive of nucleotide sequences

**Use example:** 
Retrieval of gene sequences such as TP53 and bphA1

**Strengths / Limitations:** 
Strength: 
Massive sequence repository
Limitations/ Issues: 
Annotation quality varies

### UniProtKB/Swiss-Prot, file type- FASTA, TSV, XML, Curated protein resource

**Use example:** 
Retrieval of protein records and annotation quality assessment in class activity/exercise 

**Strengths / Limitations:** 
Strength: 
High-quality reviewed annotations
Limitations/ Issues: 
Not all proteins reviewed

### Ensembl, file type- GFF, BED, FASTA, Curated genome annotation database

**Use example:** 
Examined TP53 and genomic annotations on GRCh38

**Strengths / Limitations:** 
Strength: 
Rich genomic annotations and BioMart export
Limitations/ Issues: 
Interface changes across versions

---

## Genome and Transcriptome Analysis

### UCSC Genome Browser, file type- BED, BAM, VCF, Visual exploration of genomic features

**Use example:** 
Navigation of TP53 on hg38/GRCh38 

**Strengths / Limitations:** 
Strength: 
Extensive track visualization
Limitations/ Issues: 
Can be complex for beginners

### Ensembl Genome Browser, file type- GFF, FASTA, VCF, Genome and variant exploration

**Use example:** 
Examined transcript structures and variants for human tumour/ suppression genes 

**Strengths / Limitations:** 
Strength: 
Detailed annotations and export tools
Limitations/ Issues: 
Less track customization than UCSC

###  ClinVar, file type- VCF, XML, Clinical variant interpretation 

**Use example:** 
Analysis of disease-associated TP53 and BRCA1 variants

**Strengths / Limitations:** 
Strength: 
Clinical significance classifications
Limitations/ Issues: 
Interpretations may conflict

### (need more practice) dbSNP, file type- VCF, Variant position repository

**Use example:** 
Used to identify variant locations of seed expression in tomatoes

**Strengths / Limitations:** 
Strength: 
Comprehensive SNP collection
Limitations/ Issues: 
No clinical interpretation

### DESeq2, file type- Count Matrix (TSV/CSV), Differential expression analysis

**Use example:** 
Identification of differentially expressed genes from RNA-seq data

**Strengths / Limitations:** 
Strength: 
Primary/ Gold standard RNA-seq statistical framework
Limitations/ Issues: 
Requires replicate samples and proper design

---

## Protein Structure and Function

### AlphaFold, file type- PDB, mmCIF, AI-based protein structure prediction

**Use example:** 
Structural prediction of NPR3

**Strengths / Limitations:** 
Strength: 
Structures available for most proteins
Limitations/ Issues: 
Predictions require confidence assessment (pLDDT)

### RCSB Protein Data Bank (PDB), file type- PDB, mmCIF, Experimental protein structures

**Use example:** 
Comparison with experimentally solved NPR1 structure

**Strengths / Limitations:** 
Strength: 
Experimentally validated structures
Limitations/ Issues: 
Not all proteins have structures

### (need future practice) InterPro, file type- multi/ Multiple formats, Domain and functional annotation

**Use example:** 
Identification of NPR3 functional domains

**Strengths / Limitations:** 
Strength: 
Integrates many databases
Limitations/ Issues: 
Domain predictions are not always a functional proof

### (Want future practice) PyMOL, file type- PDB, mmCIF, Molecular visualization

**Use example:** 
Visualization of residue-level effects, such as NPR3 Arg428

**Strengths / Limitations:** 

Strength: High-quality 3D visualization

Limitations/ Issues: Learning curve

---

## Computational and Scripting Tool

### RStudio

**Use example:** 
A Bioinformatics-published article and paper were paired with an RStudio script (with very messy plant growth data). The program has flower and seed data included, and used the script suggestions of swirl (AI helper) to create readable plots of this data. Uses .csv file type.

**Strengths / Limitations:** 

Strength:  
Excellent for genomics and transcriptomics

Limitations/ Issues: 
Steep learning curve if new to programming. Opening .csv files after download can break readability (Needs to remain untouched). 

---

END 
Bottom

