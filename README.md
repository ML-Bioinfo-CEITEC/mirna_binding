# Iterative Deep Neural Network Training models miRNA Binding

Deep Learning (DL), a class of supervised learning algorithms, emerges as a new tool for deciphering functional genomics. MicroRNA regulates gene expressions by binding target miRNAs and leading to their degradation. Several ClipSeq datasets are publically available for the identification of microRNA-target interactions, e.g. ENCORI. However, microRNA binding rules are only partially understood. 

Here we rendered microRNA-target interactions from only nucleotide sequence information presented as a 2-dimensional matrix, which were used to train a DL binary classifier. Next, we applied techniques for model interpretation, showing high similarity with the current state of the art about microRNA binding rules.

Raw ClipSeq datasets may be inapt for DL model training due to the high level of background noise. Post-processing pipelines polish the signal, e.g. by removing candidates mapping on non-coding genomics regions, although reducing the dataset's size. Adversely, the dataset's size linearly influences the model's performance. We overcome this limitation by adopting a training strategy that generates and increases samples of the negative class after each iteration. The iterative strategy leads to a model of comparable performances as it was trained with 5 times more samples of the positive class.

High-quality but low-throughput datasets are recurrent in biology, especially in case of complex protocols, e.g. CLASH. Our training strategy can be extended to those experiments and potentially leading to the identification of new and cryptic microRNA binding rules.


### Contact information

CEITEC MU, RBP Bioinformatics - Panagiotis Alexiou, https://www.ceitec.eu/rbp-bioinformatics-panagiotis-alexiou/rg281
