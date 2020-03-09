# ATAC_seq
This repository contains all codes for ATAC seq. It will be updated as the pipeline is polished 

Outline of ATAC-seq pipeline

Step 1: FASTQC of downloaded samples
	see script fastqc_SNK063.sh for wrapper to do qc of all files at the same time 

Step 2: Align the reads using bowtie2
	see align script

Step 3: Samtools quality filter
	see samtools analysis of samfiles script 

Step 3.5: check % mitochondrial reads 
	
Step 4: MACS2 to call peaks
	see macs2 script to call peaks  


Step 5: Examine peaks in IGV


Step 6: Compare peaks using bedtools
	done, there's a script

Step 7: Compare peak occupancy using diffBind
see R script *important files in proper format*
