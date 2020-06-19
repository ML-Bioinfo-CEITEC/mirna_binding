# Encori Dataset

This directory contains the Encori Dataset downloaded from [ENCORI](http://starbase.sysu.edu.cn/index.php) through the Web-API cmd:  

- curl 'http://starbase.sysu.edu.cn/api/miRNATarget/?assembly=hg19&geneType=mRNA&miRNA=all' > Encori_dataset.txt

Then, the Encrori Datadase was splitted into:

1. **encori_ago2.tsv.gz**: this file contains samples targeting only Ago2 Protein. These samples were used for the training and testing of models.
2. **encori_leftover_[0-3].tsv.gz**: these files contain all other samples.

The original Encori DB can be reconstructed by concatenate the above files.
