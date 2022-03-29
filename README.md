# Phylogenomics of neotropical small felids
Scripts for phylogenomic research in the genus Leopardus. 
Snakemake code consists of six interlinked pipelines: (1) QC and mapping of raw reads (‘fastq2bam’), (2) assemblage of mitogenomes from raw reads and subsequent phylogenetic analysis (‘fastq2mtdna’), (3, 4) base calling into consensus genomes and a SNP data set (resp. ‘bam2fasta’ and ‘bam2vcf’), (5) phylogenomic analysis (‘phylogeny’), and (6) genomic diversity measures (‘diversity’). For a quick overview of each pipeline, see the associated rulegraphs. Each pipeline comes with its own Conda environment (specs_\*.txt).

https://www.researchgate.net/project/Phylogenomics-of-neotropical-small-felids

**Abstract - The use of alternative genomic markers to reconstruct the complex evolutionary history of neotropical small felids**

Tracing the evolutionary origin of species can be a challenging task, especially when these species cross-breed and thereby cloud the genetic record of their evolution. Fast-developing techniques in acquiring genetic information have improved to the point where complete genomes can be routinely sequenced. One of the upcoming questions is how to make optimal use of this massive amount of data. This research project combines the above challenges, by focusing on the complete genomes of a group of cross-breeding cat species endemic to Latin America (genus Leopardus). The objective is to optimize the use of vast genomic data to elucidate evolutionary history in a complex context of hybridization, incomplete lineage sorting and recombination. Two aims are put forward in this project: (1) use complete genomes to clarify the evolutionary relationships between the different species of small spotted cats in Latin America; (2) complement the first aim with alternative and novel methods to maximize the amount of information that can be gained from these genomic sequences. We have generated whole-genome sequences for every currently recognized species of Leopardus (8 spp.) with Illumina HiSeq short reads at medium coverage (15-20x), and more samples, including museum specimens, will we be sequenced to cover all the subspecies of both the tigrina and the pampas cat complexes. For the first aim and according to current state-of-the-art, the genomic sequences will be aligned and partitioned in windows to characterize discordant topologies, divergence times, introgression and incomplete lineage sorting along the genome. For the second aim, alternative partitions will be evaluated for their capacity to add nuance to the inferences of phylogeny, introgression and incomplete lineage sorting as achieved in the first aim. A partition based on variation in local recombination rate will be tested first, given strong indications in the literature, and two other genomic features will be selected for evaluation.

Financial support for this research is provided by Research Foundation - Flanders under grant agreement N° 1128621N.
