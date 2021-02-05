# LncLOOM 
## [Ulitsky Lab](https://www.weizmann.ac.il/Biological_Regulation/IgorUlitsky/) / [Weizmann Institute of Science](https://www.weizmann.ac.il/Biological_Regulation/IgorUlitsky/)

Developed and maintained by [Caroline Ross](mailto:caroline-jane.ross@weizmann.ac.il) and [Igor Ulitsky](mailto:igor.ulitsky@weizmann.ac.il)

## About lncLOOM
lncLOOM is a graph-based framework that uses integer linear programming to identify combinations of short motifs that are 
deeply conserved in rapidly evolving sequences. The integer programming problems are solved using [PuLP](https://pypi.org/project/PuLP/), and supports the [Gurobi solver](https://www.gurobi.com/)   

LncLOOM has been implemented in Python 2 and Python 3 and is supported on Linux/Unix-based systems:
* [LncLOOMv1.0](https://github.com/lncLOOM/LncLOOMv1) implemented in Python 2

     * Download: `git clone https://github.com/lncLOOM/LncLOOMv1.git`
     
     * [How to install and run LncLOOMv1.0](https://github.com/lncLOOM/LncLOOMv1/blob/master/README.md)

* [LncLOOMv2.0](https://github.com/lncLOOM/LncLOOMv2) implemented in Python 3

     * Download: `git clone https://github.com/lncLOOM/LncLOOMv2.git`
     
     * [How to install and run LncLOOMv2.0](https://github.com/lncLOOM/LncLOOMv2/blob/main/README.md)


## Motifs discovered using LncLOOM

1) [CHASERR](https://github.com/lncLOOM/LncLOOMv1/tree/master/Chaserr_Results)

2) [MALAT1](https://github.com/lncLOOM/LncLOOMv1/tree/master/MALAT1_Results)

3) [NORAD](https://github.com/lncLOOM/LncLOOMv1/tree/master/NORAD_Resuts)

4) [XIST](https://github.com/lncLOOM/LncLOOMv1/tree/master/XIST_Results)

5) [miRNA binding sites predicted by LncLOOM](https://github.com/lncLOOM/LncLOOMv1/tree/master/miRNA_LncLOOM_Targets) 


## Defintions of Statistical values

Definitions and troubleshooting tips for calculating motif significance can be found in [Definitions.html](https://github.com/lncLOOM/lncLOOM/edit/master/Definitions.html):
