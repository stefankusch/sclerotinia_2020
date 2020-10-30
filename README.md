## Transcriptomic analysis of *Sclerotinia sclerotiorum* and *Sclerotinia trifoliorum*

In this repository, I summarize the scripts and tools I used to perform the transcriptomic analysis of *Sclerotinia sclerotiorum* and *Sclerotinia trifoliorum*. Plotting scripts are included as well. The publication can be found [here](https://doi.org/10.1101/2020.10.29.360412).

#### Index

01. Read processing and mapping.
02. Assembly quality control by use of `Blobtools`.
03. Filtering non-expressed genes
04. Differential Expression (DE) analysis via `limma-VOOM`

#### References

- Trimmomatic [Publication](https://academic.oup.com/bioinformatics/article/30/15/2114/2390096) | [Manual](http://www.usadellab.org/cms/uploads/supplementary/Trimmomatic/TrimmomaticManual_V0.32.pdf)
- FastQC [Website](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/)
- HISAT2 [Publication](http://www.nature.com/articles/nmeth.3317)
- Samtools [Publication](https://academic.oup.com/bioinformatics/article/25/16/2078/204688) | [Manual](http://www.htslib.org/doc/)
- cuffnorm [Publication](https://www.nature.com/articles/nbt.1621)
- HTseq [Manual](https://htseq.readthedocs.io/en/release_0.11.1/count.html)
- Limma-VOOM [Publication](https://f1000research.com/articles/5-1408)
