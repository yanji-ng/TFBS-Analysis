# TFBS-Analysis
Bioinformatics analysis was conducted to investigate 'Ribosomal DNA haplotype-specific silencing due to underlying differential transcription factor binding in _Mus musculus_' as a part of the Holland Laboratory, Kings College London using JASPAR2020. 

An initial pipeline was built and tested on RUNX1 (ID MA0002.2) which adhered to findings by [Charles _et al.,_ 2022](https://doi.org/10.1016/j.molcel.2022.08.027). Single nucleotide variants (SNVs) used in the analysis were identified by [Rodriguez-Algarra _et al._, 2022](doi: 10.1186/s13059-022-02617-x). Modified rDNA, by L. Mikheeva at Holland Laboratory, was used for alignement to TF binding sites (TFBS). 

Pipeline was then up-scaled and ran on 107 TFs with the following filters: 
opts[["species"]] <- 10090
opts[["collection"]] <- "CORE"  
