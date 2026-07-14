# Spatial Binary Expression Demo

## Research question

Can binary gene expression preserve sufficient information for spatial
domain identification?

## Background

The BINARY paper suggests that complete spatially resolved gene expression
is not always necessary for identifying spatial domains.

## Dataset

The project will use one slice from the human DLPFC spatial transcriptomics
dataset.

Each slice contains:

- a spot-by-gene expression matrix;
- two-dimensional spatial coordinates;
- manual cortical-layer annotations.

## Initial comparison

1. Continuous expression + PCA + K-means
2. Binary expression + PCA + K-means
3. Continuous expression with spatial information
4. Binary expression with spatial information

## Evaluation

- ARI
- NMI
- Spatial visualization

## Current status

- Paper overview completed
- Environment preparation in progress
- Dataset not loaded yet

ChatGPT plays an important role in my demo.