# ENCORI Dataset

This directory contains the ENCORI Dataset downloaded from [ENCORI](http://starbase.sysu.edu.cn/index.php) through the Web-API cmd:  

- curl 'http://starbase.sysu.edu.cn/api/miRNATarget/?assembly=hg19&geneType=mRNA&miRNA=all' > ENCORI_dataset.txt

The ENCORI database was splitted into:

1. **encori_ago2.tsv.gz**: this file contains samples targeting only Ago2 Protein. These samples were used for the training and testing of models.
2. **encori_leftover_[0-3].tsv.gz**: these files contain all other samples.

The original ENCORI DB can be reconstructed by concatenating the above files.

How to cite ENCORI:

1. Zhou KR, Liu S, Cai L, Bin L, et al. ENCORI: The Encyclopedia of RNA Interactomes.
2. Li JH, et al.[starBase v2.0: decoding miRNA-ceRNA, miRNA-ncRNA and protein-RNA interaction networks from large-scale CLIP-Seq data](https://doi.org/10.1093/nar/gkt1248) , Nucleic Acids Res. 2014 Jan;42:D92-7.
