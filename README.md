# Phylogenetic Analysis Project

## Overview

This project involves a comprehensive phylogenetic analysis focusing on the evolutionary relationships among salamanders, frogs, and lizards. Starting with dataset compilation, subsequent steps introduce various phylogenetic methods, programs, and tools for in-depth analysis.

## Project Structure

### Dataset Compilation

- **Compile Datasets:**
  - Gather and organize datasets for salamanders, frogs, lizards and outgroup.
  - Align multiple sequences.

### Phylogenetic Methods and Tools

- **Maximal Parsimony (MP) Tree:**
  - Use PAUP* for MP tree construction.
  - Ensure datatype is set to DNA in NEXUS data file.
  - Save trees with branch lengths.

- **Maximum-Likelihood (ML) and Neighbour-Joining (NJ) Trees:**
  - Use IQTree for ML and NJ tree construction.
  - Perform ML bootstrap analysis for tree robustness.

- **Bayesian Phylogenetic Reconstruction:**
  - Utilize BEAST2 for Bayesian phylogenetic reconstruction.
  - Choose the molecular evolution model based on IQTree model selection.
  - Ensure datatype is set to DNA in NEXUS data file.

## Hypothesis Testing

**Question:**
Are salamanders more closely related to frogs than to lizards?

**Analysis:**
- Perform maximum parsimony, maximum-likelihood, and neighbour-joining analyses for each of the two genes.
- Conduct ML bootstrap analysis for tree robustness.
- Perform Bayesian phylogenetic reconstruction using BEAST2 with the selected molecular evolution model.
