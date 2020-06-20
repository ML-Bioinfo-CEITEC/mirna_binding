# store annotation used for the models.

## DataBase versions:
- TargetScan Human v7.2 [url](http://www.targetscan.org/vert_72/)
- miRBase Release 22.1 [url](http://www.mirbase.org/ftp.shtml) 
- ENCORI Database version not found [url](http://starbase.sysu.edu.cn/)

## File Description:
1. **targetscan.sanified.tsv**: derived from notebook `generate_families.ipynb` targetscan families sanified with one member per family and nucleotide U replaced to T;
2. **targetscan.sanified.fasta**: targetscan.sanified.tsv as FASTA file;
3. **microRNA.loci.hsa.grch38.gff3**: derived from miRBase;
