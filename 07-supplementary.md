---
title: Supplemental Information
teaching: 0
exercises: 0
---

## Otago Bioinformatics Spring School Directory Structure

This shows the directory structure for the Otago Bioinformatics Spring School 2025


```bash
# show directories for the first 3 levels
tree -L 3 -d obss_2025
```


```output
obss_2025/
├── commandline
│   ├── shell4b_data
│   └── shell_data
│       ├── sra_metadata
│       └── untrimmed_fastq
├── genome_assembly
│   ├── annotation
│   │   ├── mashmap
│   │   └── minimap2
│   ├── assembly_qc
│   │   └── gfastats
│   ├── cleanup
│   │   └── fcs
│   ├── data
│   └── liftoff-annotation
├── genomic_dna
│   ├── adapters
│   ├── data
│   │   └── untrimmed_fastq
│   ├── docs
│   └── results
├── intro_conda
├── intro_quarto
├── intro_r
└── rnaseq
    ├── Genome
    ├── Intro
    ├── Raw
    └── Transcriptome

29 directories

```


### Directories for Intro Bash

```bash
cd ~/obss_2025/commandline

# show files and directories of shell_data/
tree shell_data
```

```output
shell_data/
├── sra_metadata
│   └── SraRunTable.txt
└── untrimmed_fastq
    ├── SRR097977.fastq
    └── SRR098026.fastq

2 directories, 3 files

```

## REANNZ HPC and scheduling

Please refer to [https://otagobioinformaticsspringschool.github.io/intro-hpc/](https://otagobioinformaticsspringschool.github.io/intro-hpc/)
