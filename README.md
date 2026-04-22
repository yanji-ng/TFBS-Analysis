# Ribosomal DNA haplotype-specific silencing due to underlying differential transcription factor binding in _Mus musculus_
Bioinformatics analysis was conducted to investigate "Ribosomal DNA haplotype-specific silencing due to underlying differential transcription factor binding in _Mus musculus_" as a part of the Holland Laboratory, Kings College London using the JASPAR2020 database. 

An initial pipeline was built and tested on RUNX1 (ID MA0002.2) and compared to findings by [Charles _et al.,_ 2022](https://doi.org/10.1016/j.molcel.2022.08.027). The modified rDNA sequence used for alignment was created by L. Mikheeva at Holland Laboratory. Single nucleotide variants (SNVs) used in the analysis were identified by [Rodriguez-Algarra _et al._, 2022](https://link.springer.com/article/10.1186/s13059-022-02617-x).

Pipeline was then up-scaled and ran on 107 TFs with the following filters: 
opts[["species"]] <- 10090; 
opts[["collection"]] <- "CORE".
