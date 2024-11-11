# Gut Microbiome and Parkinson’s Disease Analysis

This repository contains the code, analysis, and documentation for a study on the gut microbiome composition in relation to Parkinson's disease (PD), replicating and extending findings from the study by Hill-Burns et al. (2017). The analysis aims to identify microbial community patterns and potential dysbiosis in individuals with PD compared to control subjects, factoring in key confounding variables such as age, BMI, sex, and medication use.

## Dataset

The sequencing and metadata used in this analysis are sourced from the **European Bioinformatics Institute’s European Nucleotide Archive**, under accession number **ERP016332**. This dataset includes microbial 16S rRNA sequences from a cohort of individuals with and without PD, along with relevant metadata for confounding factor adjustments.

## Code and Tools

The analysis primarily relies on **QIIME2** for microbial community profiling, with additional statistical and visualization steps conducted in **R** via Google Colab. The QIIME2 code, provided by **Sean Gibbons' lab**, follows the **Apache License 2.0**, which covers all scripts and methodological workflows used for data processing, taxonomic profiling, and diversity metrics calculation.

My own processing and additional R-based analyses, including statistical comparisons and visualizations, are also licensed under **Apache License 2.0**, ensuring open access for future research and replication purposes.

## Structure

- **Data**: Contains metadata files and links to original sequence data (no raw sequencing files are stored in this repository).
- **Scripts**: Includes Jupyter notebooks and R scripts used for processing, analysis, and visualization.
- **Outputs**: Selected results from the analysis, including taxonomic bar plots, alpha diversity metrics, and beta diversity visualizations. *(Note: Not all output files are included here; only those relevant to core findings.)*

## License

This repository, including the code and results files, is licensed under the **Apache License 2.0**. This license allows for use, distribution, and reproduction, with attribution, in any medium, provided that the license terms are followed.
