# README

In this repository, we provide a mask for regions of the rat genome that show unusually high heterozygosity. We suggest that they be masked while performing genomic analysis on the rat rn6 genome.
The coordinates correspond to the rn6 reference genome.

## Directory Contents

**The subfolder ratacessibleregionsmaskfiles/ contains recommended mask files in bed format (corresponding to coordinates for the rn6 reference genome).**
There are 8 files, one for each strain, as well as a file containing mask files representing the intersection of the 8 strains. 

The subfolder unmerged/ contains mask files created without merging segments separated by a single window of low-heterozygosity.

Methods to generate these are described in: https://www.biorxiv.org/content/early/2018/05/29/332932.1

VCF file containing called variants for the 8 strains using UnifiedGenotyper (and BWA using the rn6 reference genome for alignment) can be found here: https://www.dropbox.com/s/p1v6nexw7t61ttc/All8Rats-rn6_gVCFpool.6nt.Pooled.chrs1-20.X.Y.M.qual30.dp10.vcf.gz?dl=0

The scripts folder contains links to scripts used to generate manuscript figures, obtain variant calls, and perform analysis to obtain the high-heterozygous segments.

