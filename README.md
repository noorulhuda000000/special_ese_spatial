# SpatialInferCNV Paper Analysis and Reproduction

## Overview

This repository contains our analysis and understanding of the SpatialInferCNV paper, along with initial reproduction work based on the concepts presented in the study.

The project focuses on understanding how copy number variations (CNVs) can be inferred from spatial transcriptomics data to identify clonal populations and study their spatial organization within tissue samples.

---

## Project Objectives

* Understand the research problem addressed in the paper.
* Study the SpatialInferCNV methodology.
* Analyze the major results and figures presented by the authors.
* Reproduce selected concepts and visualizations from the paper.
* Execute and evaluate the SpatialInferCNV tutorial workflow.

---

## Work Completed

### Paper Understanding

The following aspects of the paper were studied and summarized:

* Research background
* Problem statement
* Spatial transcriptomics concepts
* Copy Number Variations (CNVs)
* Clone identification methodology
* SpatialInferCNV workflow
* Results and biological findings
* Figure interpretation and analysis

Detailed notes can be found in the `paper_summary` directory.

---

### Colab-Based Reproductions

To better understand the methodology presented in the paper, several simplified reproductions were implemented using Python in Google Colab.

#### 1. CNV Heatmap Simulation

A simulated CNV heatmap was generated to visualize copy number gains and losses across multiple clones.

#### 2. Hierarchical Clustering

Hierarchical clustering was performed on simulated CNV profiles to demonstrate clone identification using dendrogram analysis.

#### 3. Spatial Clone Mapping

A synthetic tissue grid was generated to visualize how different clones can occupy distinct spatial regions.

#### 4. Clone Size Distribution

A clone abundance plot was generated to compare the relative sizes of different clonal populations.

---

### SpatialInferCNV Tutorial

The official SpatialInferCNV tutorial workflow is currently being evaluated.

Tutorial outputs and observations will be added to the repository as they become available.

---
## My Simplified Reproduction of the Paper

Since the complete SpatialInferCNV workflow requires specialized R packages, spatial transcriptomics datasets, and significant computational resources, a simplified conceptual reproduction was implemented in Google Colab using Python.

The goal was not to exactly reproduce the original paper results, but to recreate and understand the core ideas presented by the authors.

The following concepts were reproduced:

### CNV Heatmap

A simulated Copy Number Variation (CNV) heatmap was generated to understand how copy number gains and losses can be visualized across different clones. This was inspired by the CNV visualizations used throughout the paper to identify genetically distinct populations.

### Clone Identification Through Clustering

Hierarchical clustering was performed on simulated CNV profiles to understand how spots with similar genomic patterns can be grouped into clones. This reproduces the basic concept behind clone discovery in the SpatialInferCNV workflow.

### Spatial Clone Visualization

A synthetic tissue grid was created to visualize how different clones can occupy distinct spatial regions within tissue. This was inspired by the spatial clone maps presented in the paper.

### Clone Abundance Analysis

A clone size distribution plot was generated to compare the relative abundance of different clones. This demonstrates the concept of clonal heterogeneity discussed in the study.

### Learning Outcome

These reproductions provided a practical understanding of the major analytical concepts used in the paper, including CNV visualization, clone identification, spatial organization of clones, and clonal heterogeneity.
these can be found in the ipynb file uploaded.
