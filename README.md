# Alignment_variantcalling_annotation
Working on the Galaxy platform, I aligned three sets of targeted re-sequencing data to a reference genome called hg19, called the variants, and annotated them. The entire workflow is available on Galaxy (https://usegalaxy.org/u/kywertheim/w/genomic-data-science-with-galaxy).

Input files: Coriell-NA12877_R1.fastq, Coriell-NA12877_R2.fastq, Coriell-NA12878_R1.fastq, Coriell-NA12878_R2.fastq, Coriell-NA12880_R1.fastq, and Coriell-NA12880_R2.fastq are the sequence data files. The data files are in the compressed files (data1.zip, data2.zip, and data3.zip).

Analysis file: GalaxyWorkflow_Alignment_VariantCalling_Annotation.ga contains the entire workflow.

Output file: FilteredVariants.vcf contains the variants.
