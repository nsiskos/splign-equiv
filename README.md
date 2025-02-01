# splign-equiv
This is an attempt to format SAM output of magicblast.

Start by comparing an mRNA (or a set of mRNAs) in FASTA format, with a subject that can be a chromosome (FASTA format) or a BLAST database.

```Shell
# mRNA to chromosome
$ magicblast -query QUERY.fa -subject SUBJECT.fa
```
or
```Shell
# mRNA to BLAST db
$ magicblast -query QUERY.fa -db BLASTDB

```

Then, paste the SAM output of Magic-BLAST in the textarea and click "Read Str" to start exploring the alignments. 

Alternatively, you can press "Load example 1" or "Load example 2" to see how it works!
