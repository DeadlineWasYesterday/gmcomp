# gmcomp: gene model comparisons
For comparing gene models across different annotations of the same genome.

## Install
```
pip install gmcomp
```

## Usage
```
gmcomp annotation_file1.gff annotation_file2.gff annotation_file3.gff
```

## Description
Currently accepts gff/gtf files. The program will export a table of shared gene models across annotations, graphs for number of gene/transcript matches with a positional start/end offset from 0-5000, and graphs for fraction of gene/transcript overlaps from one annotation to another. 

## Dependencies
numpy, pandas, matplotlib and seaborn

## Example Output

On four sets of genome annotations on the <i>Arabidopsis thaliana</i> genome.

Gene offsets:

<img src="https://ava.genome.arizona.edu/UniPhy/web/gene_offsets.png" width="400">

Shared feature counts:

<img src="https://ava.genome.arizona.edu/UniPhy/web/common_feature_counts.png" width="400">


Gene overlaps: 

<img src="https://ava.genome.arizona.edu/UniPhy/web/gene_overlaps.png" width=400>