# ASSIGNMENT

Download the file [sample_lane.fastq.gz](https://github.com/b97pla/recruitment/blob/bioinfo-vik-2019/sample_lane.fastq.gz). This is an example of a file containing sequence read data in FASTQ format. 

Briefly, each sequence read consists of four rows, where the first row is a header, the second row is the nucleotide sequence, the third row is an optional header string and the fourth row contains ascii-encoded base-quality values. The first row (the header) always starts with a "@"-character and the third row always start with a "+"-character.
The header string for each read contains some metadata for the read as well as the barcode sequence for the read.

1. Write a script, in a language of your choice, that performs demultiplexing (i.e. sorting the reads into separate files according to barcode) of the sample FASTQ file with the help of the barcode-to-sample translation provided.  
2. Write a bash one-liner that counts the number of reads in the FASTQ file.
3. Visualize two distribubutions in R, see [this gist](https://gist.github.com/johandahlberg/e227ff764b79e4fed5ea460706cfd4d7)
