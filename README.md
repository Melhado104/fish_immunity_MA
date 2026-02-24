# Study Scope
This meta-analysis synthesises evidence across multiple pharmaceutical classes, including antibiotics, antidepressants, contraceptives, and anti-inflammatories.
Immune outcomes were categorised into: cytokines, white blood cell counts, humoral-mediated responses, and cell-mediated responses.
Both average immunocompetence and inter-individual variability were evaluated to determine whether pharmaceutical exposure alters immune function in fish.

The repository described below contains the data and code used for this study.
For questions regarding data reuse or analytical details, please contact:
Gabriel Melhado
School of Biological Sciences
Monash University
Australia

gabriel.melhado@gmail.com

## Data
This folder contains all datasets generated during the data extraction and preparation phases. Files include:
Cleaned datasets used for effect size computation;
Moderator classification files (e.g., pharmaceutical class, immune trait category);
Variables include: study identifiers, species, pharmaceutical class, exposure duration and concentration, immune trait category, sample size, mean, standard deviation

## R
This directory contains all R scripts and R Markdown files necessary to reproduce the analyses.
The workflow generally follows this order:
Data cleaning and preparation
Effect size calculation
Random-effects meta-analysis models
Moderator analyses (uni- and multi-moderator models)
Heterogeneity estimation
Publication bias assessment (e.g., funnel plots, Egger-type tests)
Influence diagnostics and leave-one-out analyses
Figure generation

## Figures
This directory stores all figures generated in the manuscript and supplementary materials.
Figures are saved in high-resolution formats (PDF and PNG/JPEG) suitable for publication.
