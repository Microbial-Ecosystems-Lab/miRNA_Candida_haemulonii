# miRNA_Candida_haemulonii

miRNA RNA-seq data analysis

## Quality control analysis before and after trimming/clipping

BEFORE:
[https://rawcdn.githack.com/Microbial-Ecosystems-Lab/miRNA_Candida_haemulonii/cba8da055cc0e922d4a908860236ede8fe20dc3f/multiqc_report.html](https://rawcdn.githack.com/Microbial-Ecosystems-Lab/miRNA_Candida_haemulonii/f1367de993ebb4e7702d06849d3534c5eb068297/multiqc_report_raw_reads.html)

AFTER:
[$](https://rawcdn.githack.com/Microbial-Ecosystems-Lab/miRNA_Candida_haemulonii/f1367de993ebb4e7702d06849d3534c5eb068297/multiqc_report_AFTER_trimming_clipping.html)https://rawcdn.githack.com/Microbial-Ecosystems-Lab/miRNA_Candida_haemulonii/f1367de993ebb4e7702d06849d3534c5eb068297/multiqc_report_AFTER_trimming_clipping.html


## Mapping reads to reference genome (miRDeep2 tool)

$ mapper.pl CH1_VE.fastq_output_truseq3.fastq -e -h -j -l 18 -m -p reference_genome/genome.fa -m -s reads.fa -t reads_vs_genome.arf -v

$ miRDeep2.pl reads.fa reference_genome/genome.fa reads_vs_genome.arf none none none 2>report.log
