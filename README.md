# Single-cell analysis of the immune response in COVID-19

A comprehensive single-cell and transcriptome, surface proteome and T and B lymphocyte antigen receptor analysis of >780,000 peripheral blood mononuclear cells from 130 patients across a spectrum of SARS-CoV-2 disease severity.

> **Note:** This project is for learning purposes only. Due to compute and RAM limits, only a subset of the original dataset has been used in this analysis.

---

## Dataset Information

| Field           | Detail                                                                                   |
| --------------- | ---------------------------------------------------------------------------------------- |
| **Publication** | Stephenson et al., _Nature Medicine_ (2021)                                              |
| **DOI**         | [https://doi.org/10.1038/s41591-021-01329-2](https://doi.org/10.1038/s41591-021-01329-2) |
| **Dataset ID**  | GEO: GSE171648 (multi-omics single-cell data)                                            |
| **Sample size** | >780,000 cells from 130 patients _(Subset used for this tutorial)_                       |
| **Modality**    | scRNA-seq + surface proteome + T/B cell receptor sequencing                              |

## Notebook Overview

This notebook demonstrates a typical single-cell RNA-seq analysis workflow using a subset of the data to accommodate compute and RAM constraints. It includes:

- **Data pre-processing**: quality control metrics, gene and cell filtering
- **Dimensionality reduction & clustering** to explore the dataset structure
- **Visualization** of key features

## Requirements

install uv and use `uv sync`

---

## References

- Stephenson E, Reynolds G, Botting RA et al. Single-cell multi-omics analysis of the immune response in COVID-19. _Nat Med_ 27:904–916 (2021). [DOI](https://doi.org/10.1038/s41591-021-01329-2)
