# Bycom
methylcytosine calling (5mC calling) from BS-seq.
Bycom can do methylcytosine calling from BS-seq (WGBS and RRBS), and either unmapped reads (FASTQ) or mapped reads (SAM/BAM) could be permitted for the input data. Certain SNPs (C>A/G) can also be selected in the output.
1. There's no softwares or methods identify methylcytosines considering the cell heterozygosis caused by multicellular sequencing. Bycom introduced it along with the sequencing errors and unconverson rate based on the Bayesian model.
2. Several parameters in Bycom could be set as what the users want to, such as depth threshold, quality control value, conversion rate, processor number.
3. Bycom do the mapping based on BSMAP, and provide the parameters using in the alignment.
# Website
https://sourceforge.net/projects/bycom/
