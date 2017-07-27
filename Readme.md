## Sample analysis
After trial and error of trying to remove barcodes from the raw files a new approach of using the full.fasta and full.qual files will be done.

**Convert files to FASTQ**
```fish
convert_fastaqual_fastq.py -f ../originals/fasta-qual-mapping-files/062917CM515F-full.fasta -q ../originals/fasta-qual-mapping-files/062917CM515F-full.qual -o fastq
```