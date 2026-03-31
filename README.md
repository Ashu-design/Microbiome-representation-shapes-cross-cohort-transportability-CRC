# Gut_Publication

A notebook workflow for **colorectal cancer (CRC) gut metagenomics benchmarking and publication-ready analysis** using datasets from **curatedMetagenomicData / ExperimentHub**.

This project focuses on:
- acquiring and curating CRC-relevant metagenomic cohorts,
- building cross-study benchmark pipelines,
- evaluating transfer across cohorts and feature representations,
- running post-hoc statistical analyses,
- generating publication-style figures,
- recalibration and add-on analyses,
- source-selection / deployment-oriented downstream analyses.

## Notebook

Main notebook: `Gut_Publication.ipynb`

The notebook is organized into the following sections:

1. **Data acquisition**  
   Downloads and prepares CRC-relevant metagenomic data and metadata from ExperimentHub / curatedMetagenomicData-related resources.

2. **Main final CRC benchmark pipeline**  
   Builds benchmark models across multiple feature types such as:
   - relative abundance,
   - pathway abundance,
   - pathway coverage,
   - marker abundance,
   - marker presence,
   - gene families.

3. **Combination transfer**  
   Evaluates transfer/generalization across cohorts and study combinations.

4. **Post-hoc augmentation / statistics**  
   Adds statistical analyses and diagnostic summaries after the core benchmark pipeline.

5. **Figure block**  
   Produces publication-style visualizations and figure assets.

6. **Recalibration / add-on analysis**  
   Performs recalibration and supplementary model analyses.

7. **Final source-selection / deployment suite**  
   Adds publication-safe tables/figures and source-selection style analyses.

8. **Adjusted regression / extra analyses**  
   Includes additional regression-based analyses for interpreting shifts in performance.

## Expected environment

The notebook was written primarily for **Google Colab**, based on paths such as:
