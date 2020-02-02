# lncRNA_annotation_cufflinks_nf

To run the pipeline: <br>


```{r}

nextflow run cbcrg/lncRNA-Annotation-nf --reads './regeneration/reads/*read{1,2}.fastq.gz' --genome ./regeneration/genome/dm6.fa --annotation './regeneration/annotation/dmel.r6.29.gtf' --output regene_results/ -with-singularity -profile crg


```




