# miRNA_Candida_haemulonii

miRNA RNA-seq data analysis

## Quality control analysis before and after trimming/clipping

BEFORE:
https://rawcdn.githack.com/Microbial-Ecosystems-Lab/miRNA_Candida_haemulonii/cba8da055cc0e922d4a908860236ede8fe20dc3f/multiqc_report.html

AFTER:
$


## Create a mapping file with ARF format (miRDeep2 tool)

Convert fastq to fasta (FASTX-toolkit)

$ fastq_to_fasta -i file.fastq -o file.fasta
