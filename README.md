# Cancer Subtype Prediction via Unsupervised Learning

Dimensionality reduction and clustering applied to gene expression data to predict cancer subtypes — final project for an M.S. Data Science unsupervised learning course.

## Overview

High-dimensional genomic data presents a classic unsupervised learning challenge: can we recover meaningful biological structure (cancer subtypes) from raw gene expression measurements without using labels during training? This project applies SVD-based dimensionality reduction followed by logistic regression to benchmark how well the discovered structure maps to known subtypes.

## Approach

- Applied **Singular Value Decomposition (SVD)** to reduce high-dimensional gene expression features into a compact latent representation
- Used clustering to explore natural groupings in the reduced space
- Trained a **logistic regression** classifier on the latent features to evaluate how well unsupervised structure corresponds to labeled cancer subtypes
- Assessed model performance with appropriate classification metrics

## Tech Stack

- **Libraries:** scikit-learn, NumPy, pandas, matplotlib
- **Environment:** Jupyter Notebook
- **Key concepts:** SVD, dimensionality reduction, unsupervised clustering, logistic regression, genomic data

## Context

Final project for an M.S. in Data Science unsupervised learning course. The biomedical framing was personally motivated — my professional background is in assay development and molecular biology, so applying ML to genomic data felt like a natural bridge between both domains.

## Why It Matters

Unsupervised discovery of cancer subtypes from expression data is a real and active research problem. This project is a simplified demonstration of the core approach, not a clinical tool — but it reflects genuine familiarity with the underlying biology and methodology.
