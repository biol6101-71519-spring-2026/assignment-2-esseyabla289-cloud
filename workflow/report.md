Report on overall read quality and mapping rates

Based on the multiqc.html report, looking at the Phred score accross most of the reads
were more than 30 indicating that most of the bases are of good quality.
Per the FastQC mean quality scores, towards the higher base pairs the quality drops. 

With samtools (ecoli_k12_flagstat.txt), it shows that about 70.43% of the readas 
were successfully mapped to the reference genome however the properly mapped reads 
had a percentage of 12.73% which is not the best.This is indicative of pairing issues.
This makes it a concern and probably causes may have been due to incorrect pairing 
during alignment or something went wrong during one of the processes.
