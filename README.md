# Code used and files generated for "Patterns in the Juan Fernandez fur seal (Arctophoca philippii philippii) faecal microbiome"

Constanza Toro-Valdivieso (1)
Frederick Toro (2)
Samuel Stubbs (3)
Eduardo Castro-Nallar (4)
Barbara Blacklaws (1)

1. Department of Veterinary Medicine, University of Cambridge, UK
2. Facultad de Ciencias de la Vida, Universidad Andres Bello, Chile
3. Department of Infectious Disease Epidemiology, London School of Hygiene and Tropical Medicine, UK
4. Center for Bioinformatics and Integrative Biology, Universidad Andres Bello, Chile
-------------------------------------------------------------------------------------
Raw sequences can be accessed via the European Nucleotide Archive (ENA) under the study accession PRJEB365555.

The repository contains the following folders:

- Fasqc   
*These are the compressed html files generated with FastQC to look at the sequence quality:  
-- fastqc_2017.tar.xz  
-- fastqc_2018.tar.xz  
  
- Qiime  
*This folder contains the metada files used in Qiime (one per year and one combing both years of collection), the script, and the folders containing the output files that can be visualised directly [here](https://view.qiime2.org/)  
-- JFFS_2017.tsv  
-- JFFS_2018.tsv  
-- JFFS_metadata_qiime2.tsv  
-- Qiime_script  
-- qzv_files  
--- Separate  
---- 2017  
----- demux-JFFS-2017.qzv  
----- rep-seqs-2017.qzv  
----- stats-dada2-2017.qzv  
----- table-dada2-2017.qzv  
---- 2018  
----- demux-JFFS-2018.qzv  
----- rep-seqs-2018.qzv  
----- stats-dada2-2018.qzv  
----- table-dada2-2018.qzv  
--- Combine  
---- merged-table.qzv  
---- rep-seq-merged.qzv  
---- rooted-tree.qza  
---- unrooted-tree.qza  
---- taxonomy_silva132.qzv  
  
- R_stats
*This folder contains all the code used in the statistical analysis done in R. There is one folder per step and each of them include and html and a rdm file version.  
-- JFFS_microbiome_Script1  
--- JFFS_microbiome_Script1.html
--- JFFS_microbiome_Script1.rdm
