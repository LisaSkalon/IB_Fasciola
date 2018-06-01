# IB_Fasciola
This is the repo dedicated to Fasciola transposable elements 


## Methods

### F.hepatica RNA-seq data
For our purposes we used public data which can be found in SRA NCBI archive.  
Acsessions: [ERX535560](https://www.ncbi.nlm.nih.gov/sra/?term=ERX535560), [ERX535563](https://www.ncbi.nlm.nih.gov/sra/?term=ERX535563), [ERX535561](https://www.ncbi.nlm.nih.gov/sra/?term=ERX535561), [ERX535360](https://www.ncbi.nlm.nih.gov/sra/?term=ERX535360), [ERX535363](https://www.ncbi.nlm.nih.gov/sra/?term=ERX535363), [ERX535362](https://www.ncbi.nlm.nih.gov/sra/?term=ERX535362), [ERX535371](https://www.ncbi.nlm.nih.gov/sra/?term=ERX535371), [ERX535370](https://www.ncbi.nlm.nih.gov/sra/?term=ERX535370).
Info: ...

### List of *F.hepatica* TEs
As well we applied fasta file with repeatitive elements of *F.hepatica* genome, created earlier with help of RepeatMasker tool.

### Project workflow 
Short outline of our work:

First of all, row reads of 4 developmental stages were filtered using Trimmomatic and FastQC for quality control. Differential expression analysis was performed with two separate methods: kallisto + sleuth and TEtools + DeSeq2. To analyze any TEs that show change in expression across the different stages, likelihood ratio test (LRT) was implemented. In the end lists of significant TEs (FDR>0.05), which are differentially expressed across developmental stages, was obtained. 
All steps can be found in....

### System requirements
* python v.3.6
* R v.3.4.4
* Trimmomatic v.0.36
* FastQC v.0.11.7
* kallisto v.0.44.0 
* sleuth v.0.29.0
* TEtools v.3 
* DeSeq2 v.1.18.1

## Results
Both approaches to DE analysis show similiar results.
All results can be found in ...
....

