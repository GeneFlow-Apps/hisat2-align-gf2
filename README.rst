HISAT2 Align GeneFlow App
====================

Version: 2.2.1-01

This GeneFlow app wraps the HISAT2 align tool.

Inputs
------

1. input: Sequence FASTQ File - A sequence file in the FASTQ file format.

2. pair: Paired-End Sequence FASTQ File - A paired-end sequence file in the FASTQ file format.

3. reference: HISAT2 Reference Index - A directory that contains a HISAT2 reference index. This index includes multiple files. 

Parameters
----------

1. threads: CPU Threads - The number of CPU threads to use for sequence alignment. Default: 2.
 
2. output: Output SAM File - The name of the output SAM file to which alignment results should be written. Default: output.sam.

