# BINF6210-Assignement5
This is the repository for BINF6210 Assignment 5.

I created a branch called Developments on Nov 21.

Obtained the data set from NCBI on Dec 3.


**Introduction**

The evolution of nuclear genes is generally slower than that of mitochondrial genes which can differ their phylogenetic trees(Lin & Danforth, 2004). Because of this, researchers often estimate phylogenetic relationship based on both of these genes for more accurate result. However, research about the discordance between different mitochondrial-gene trees are relatively limited.

COI (Cytochrome Oxidase I) and CytB (Cytochrome b) are both mitochondrial genes that are commonly used for phylogenetic studies, species identification, and evolutionary biology in birds. Whereas, the evolutionary rates between these two genes are different across more than 300 species in avian orders: COI evolves 14% slower than CytB on average (Lavinia et al., 2016). This means choosing different marker mitochondrial genes can also make the estimated phylogenetic trees vary.

To further explore the discordance of COI-gene trees and CytB-gene trees in a specific genera of bird, I use COI and CytB sequences data sets of Acipenser which are downloaded from NCBI and apply functions from packages such as “DECIPHER”, “ape”, and “dendextend” to make a tanglegram for examining topological congruence between the two phylogenetic trees draw from COI and CytB data sets.

**Description of Data Set**

The data set I choose for this project is the DNA sequences of COI gene and CytB gene in Acipenser from NCBI, and this data set is obtained on December 3, 2023. Here I use rentrez package and functions in Entrez_Functions.R, a course material, to obtain the data in this R script. I also limited the sequence lengths of the two genes to exclude whole genome sequences: the range of sequence length is 500-700 for COI gene and is 600-1200 for CytB gene.
