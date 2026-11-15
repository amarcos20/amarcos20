```text
>afonso_marcos | bioinformatics | University of Porto (FCUP / ICBAS) | 3rd year
ATGGCTCGTGCTACTCATTAGAATTAA
```

<sub>Translate it, reading TAG as pyrrolysine.</sub>

I study bioinformatics in Porto. Most of what I enjoy is taking data that
already exists and checking it properly: the work directory of a failed
pipeline, a genome assembly next to its reference, a classifier that only
looks good because the classes are imbalanced.

## Now

- Writing a [MultiQC](https://github.com/MultiQC/MultiQC) module for
  ABRicate, the antimicrobial resistance and virulence gene screener
  ([MultiQC#3735](https://github.com/MultiQC/MultiQC/issues/3735)).
- Building [nf-diagnose-mcp](https://github.com/amarcos20/nf-diagnose-mcp),
  a read-only server that works out why a Nextflow / nf-core run failed
  from the files it left on disk.
- Learning more deep learning and transcriptomics, with an eye on bacterial
  genomics for my final-year project.

## Selected work

| Project | What it is | Result |
|---|---|---|
| [nf-diagnose-mcp](https://github.com/amarcos20/nf-diagnose-mcp) | MCP server for diagnosing failed Nextflow runs: failed tasks, exit codes, enforced limits, tail of the logs | Tested on real nf-core runs, locally and on a SLURM cluster |
| [FCUP-DL-ML2](https://github.com/amarcos20/FCUP-DL-ML2) | Heart murmur detection from phonocardiograms (CirCor DigiScope), CNN and RNN on log-mel spectrograms | Weighted accuracy 0.75 (CNN) and 0.79 (RNN) on a test fold used once; baseline 0.50 |
| [FFUP-OMICS-ALPHAFOLD](https://github.com/amarcos20/FFUP-OMICS-ALPHAFOLD) | AlphaFold 2 vs AlphaFold 3: pLDDT, RMSD, TM-score and heme geometry | [Report and slides](https://amarcos20.github.io/FFUP-OMICS-ALPHAFOLD/) |
| [FCUP-ML-ML1](https://github.com/amarcos20/FCUP-ML-ML1) | CART decision tree written from scratch, then modified for class imbalance | Three modifications compared against the standard tree |
| [FCUP-EPIDEMIOLOGY](https://github.com/amarcos20/FCUP-EPIDEMIOLOGY) | Protocol for a case-control study on caffeine intake and Parkinson's disease | [Web version](https://amarcos20.github.io/FCUP-EPIDEMIOLOGY/) |

## How I like to work

- One command from raw data to final table, inside a container (Apptainer,
  Conda environments with pinned versions).
- The test set is opened once, at the end.
- Tools that read before they write. If something can be diagnosed without
  touching it, it should be.
- Results go in data files, not hard-coded in notebooks.

## Tools

**Languages:** Python, R, Bash, SQL, Java<br>
**Analysis and ML:** pandas, scikit-learn, PyTorch, Biopython<br>
**Pipelines and environments:** Nextflow / nf-core, Snakemake, Apptainer, Docker, Conda, SLURM, Galaxy<br>
**Data:** FASTA/FASTQ, SAM/BAM, VCF, GFF/GTF, NCBI, AlphaFold DB

## Away from the screen

Training for a marathon, alongside strength training and football.

## Contact

[afonso20marcos@gmail.com](mailto:afonso20marcos@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/afonsomarcos20)
