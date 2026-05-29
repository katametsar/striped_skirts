# Computational Analysis of Estonian Striped Skirt Patterns

## Overview

This repository contains a computational workflow for analysing visual similarities between Estonian striped skirt textiles and English Norwich callimanco fabrics.

The workflow combines image preprocessing, colour analysis, stripe structure analysis, deep visual embeddings, and machine learning techniques to investigate historical textile patterns.

The project forms part of a broader digital humanities research effort exploring potential visual relationships between imported English textiles and Estonian folk costume traditions.

---

## Research Questions

* Can computational methods identify visually similar striped textile patterns across collections?
* Which visual characteristics contribute most strongly to similarity?
* Can machine learning support traditional textile research and cultural heritage studies?

---

## Data Sources

The workflow uses image collections from:

* Estonian National Museum (ERM)
* MUIS (Estonian Museums Information System)
* Historical Norwich callimanco textile collections
* Museum catalogues and textile research publications

---

## Repository Contents

| File                | Description                           |
| ------------------- | ------------------------------------- |
| Triibuanalyys.ipynb | Main Jupyter Notebook workflow        |
| triibuanalyys.py    | Python implementation of the workflow |
| requirements.txt    | Python dependencies                   |
| README.md           | Project documentation                 |

---

## Methods

The workflow includes:

1. Image collection and preparation
2. Textile stripe extraction
3. Colour palette analysis
4. Stripe rhythm analysis
5. Deep visual embeddings using ResNet50
6. Similarity scoring
7. Clustering and pattern exploration
8. Interpretation of results in a cultural-historical context

---

## Environment

* Python 3
* Jupyter Notebook
* Google Colab

Main libraries:

* pandas
* numpy
* matplotlib
* scikit-learn
* torch
* torchvision
* pillow
* scipy
* opencv-python

---

## Reproducibility Notes

Several workflow stages are fully reproducible, including:

* image preprocessing
* feature extraction
* similarity calculations
* clustering

Some stages involve researcher decisions, such as:

* image selection
* crop boundaries
* interpretation of similarity results

---

## Author

Kata Maria Metsar, Tiina Kull

Estonian National Museum (ERM)

---

## License

CC BY 4.0
