# Differential expression analysis between three RNA-Seq results from three wild type of Arabidopsis thaliana plants

Project.html is the document with the Differential expression analysis.
Data_quiality have detailed information about the data.

Abstract of the pratice: 

Using data from the PRJNA821620 project(NCBI), we performed a differential expression analysis between three RNA-Seq results from three wild type (WT) Arabidopsis thaliana plants and using three mutants called phod1 (phosphate deficiency 1). These mutants showed an expression of a gene (PHT1;4) related to phosphorus deficiency in a phosphate-rich medium, suggesting an alteration in a regulatory component. Our objective is to identify the differences in gene expression that exist between both groups and identify their ontology to try to observe the mechanisms through which this mutant is capable of expressing a gene that in principle should not do so. To do this we follow the “RNA seq” pipeline (ref), where we use MultiQC to observe the quality of our raw data without adapters, Kallisto to assemble this with a reference transcriptome, carry out the differential expression analysis with DESeq2 and finally do a go functional analysis. Our results indicate that the phod1 mutant has a higher expression compared to the WT in genes related to cellular responses to chemical stimuli.


Authors: Onna Nayyu Leyva Alcantara; Undergraduate student in Genomic sciences at Universidad Nacional Autonoma de México (UNAM)
         Rodrigo Aguilar Dias      ; Undergraduate student in Genomic sciences at Universidad Nacional Autonoma de México (UNAM) 
         Aura Belem Aguilar Roldan ; Undergraduate student in Genomic sciences at Universidad Nacional Autonoma de México (UNAM)
