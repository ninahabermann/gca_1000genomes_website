---
title: "Why are there more than one set of fastq files associated with an individual?"
faq_tags:
  - data-access
  - fastq
  - sequence
faq_related:
  - how-much-sequence-data-has-been-generated-single-individuals
  - where-are-your-sequence-files-located
  - what-do-names-your-fastq-files-mean
---
                    
Many of our individuals have multiple fastq files. This is because many of our individual were sequenced using more than one run of a sequencing machine.

Each set of files named like ERR001268_1.filt.fastq.gz, ERR001268_2.filt.fastq.gz and ERR001268.filt.fastq.gz represent all the sequence from a sequencing run. 

When a individual has many files with different run accessions (e.g ERR001268), this means it was sequenced multiple times. This can either be for the same experiment, some centres used multiplexing to have better control over their coverage levels for the low coverage sequencing, or because it was sequenced using different protocols or on different platforms.

For a full description of the sequencing conducted for the project please look at our [sequence.index file](http://www.1000genomes.org/faq/what-sequence-index-file)
