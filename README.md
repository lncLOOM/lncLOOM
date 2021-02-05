# LncLOOM 
## [Ulitsky Lab](https://www.weizmann.ac.il/Biological_Regulation/IgorUlitsky/) / [Weizmann Institute of Science](https://www.weizmann.ac.il/Biological_Regulation/IgorUlitsky/)

Developed and maintained by [Caroline Ross](mailto:caroline-jane.ross@weizmann.ac.il) and [Igor Ulitsky](mailto:igor.ulitsky@weizmann.ac.il)

## About lncLOOM
lncLOOM is a graph-based framework that uses integer linear programming to identify combinations of short motifs that are 
deeply conserved in rapidly evolving sequences. The integer programming problems are solved using [PuLP](https://pypi.org/project/PuLP/), and supports the [Gurobi] solver(https://www.gurobi.com/)   

LncLOOM has been implemented in Python 2 and Python 3 and is supported on Linux/Unix-based systems:
* [LncLOOMv1.0](https://github.com/lncLOOM/LncLOOMv1) implemented in Python 2

     * Download: `git clone https://github.com/lncLOOM/LncLOOMv1.git`
     
     * [How to install and run LncLOOMv1.0](https://github.com/lncLOOM/LncLOOMv1/blob/master/README.md)

* [LncLOOMv2.0](https://github.com/lncLOOM/LncLOOMv2) implemented in Python 3

     * Download: `git clone https://github.com/lncLOOM/LncLOOMv2.git`
     
     * [How to install and run LncLOOMv2.0](https://github.com/lncLOOM/LncLOOMv2/blob/main/README.md)

## Defintions of Statistical values

Definitions and troubleshooting tips for calculating motif significance are also given in [Definitions.html](https://github.com/lncLOOM/lncLOOM/edit/master/Definitions.html):

P(i): Probability of finding the exact motif, at the same depth, in a random set of sequences that have the same percentage identities as the input sequences

E(i): Probability of finding any combination of the same number of motifs of the same length, or longer, at the same depth, in a random set of sequences that have the same percentage identities as the input sequences

P(r): Probability of finding the exact motif, at the same depth, in a random set of sequences that have the dinucleotide composition as the input sequences

E(r): Probability of finding any combination of the same number of motifs of the same length, or longer, at the same depth, in a random set of sequences that have the same dinucleotide composition as the input sequences

## Motifs discovered using LncLOOM

1) [Chaserr](https://github.com/lncLOOM/LncLOOMv1/tree/master/Chaserr_Results)

2) [MALAT1](https://github.com/lncLOOM/LncLOOMv1/tree/master/MALAT1_Results)

3) [NORAD](https://github.com/lncLOOM/LncLOOMv1/tree/master/NORAD_Resuts)

4) [XIST](https://github.com/lncLOOM/LncLOOMv1/tree/master/XIST_Results)

5) [miRNA binding sites predicted by LncLOOM](https://github.com/lncLOOM/LncLOOMv1/tree/master/miRNA_LncLOOM_Targets) 

