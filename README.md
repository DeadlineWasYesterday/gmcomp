# gmcomp: gene model comparisons
For comparing gene models across different annotations of the same genome.

## install
```pip install gmcomp```

## usage
```gmcomp annotation_file1.gff annotation_file2.gff annotation_file3.gff```

## description
Currently accepts gff/gtf files. Will export a table of shared gene models across annotations, graphs for number of gene/transcript matches with a positional start/end offset from 0-5000, and graphs for fraction of gene/transcript overlaps from one annotation to another. 