# Malaria Cell Classification

An educational computer-vision project using the Kaggle **Cell Images for Detecting Malaria** dataset.

This repository is being built as a learning project. The goal is to understand the reasoning behind each step—not to copy a notebook or hide the work behind an end-to-end script.

## Learning contract

- We explain the concept before writing the implementation.
- We start with data understanding and a classical baseline before deep learning.
- Every experiment records its data split, preprocessing, model, metrics, and limitations.
- We do not claim that this project is a clinical diagnostic system.
- Dataset files and model checkpoints stay out of Git; the repository contains reproducible download and processing instructions instead.

## Project question

Can a computer-vision model distinguish between the two image classes in the dataset: `Parasitized` and `Uninfected`?

This is a research and learning question about the provided image collection. It is not a medical diagnosis claim.

## Dataset

- Kaggle reference: [`iarunava/cell-images-for-detecting-malaria`](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria)
- The dataset contains segmented cell images organized by class.
- We will inspect the source, label structure, image dimensions, class balance, and licensing before training.

The dataset is not committed to this repository. Download instructions will be added during the data-ingestion milestone.

## Milestones

- [x] M0 — Project scaffold and learning contract
- [ ] M1 — Reproducible environment and dataset inspection
- [ ] M2 — Exploratory data analysis and image-quality checks
- [ ] M3 — Classical baseline and evaluation metrics
- [ ] M4 — Small CNN from scratch
- [ ] M5 — Transfer learning and controlled experiments
- [ ] M6 — Error analysis, explainability, and limitations
- [ ] M7 — Reproducible packaging, final documentation, and resume-ready presentation

## Planned repository structure

```text
data/          Downloaded data; intentionally ignored by Git
notebooks/     Short, exploratory learning notebooks
src/           Reusable project code
tests/         Tests for reusable code
configs/       Experiment configuration files
reports/       Figures and written experiment reports
```

## Current status

Milestone M0 is complete. The next learning task is to create a Python 3.12 environment and verify the basic scientific-computing stack before downloading data.

## Responsible-use note

Medical images can contain sampling bias, labeling errors, acquisition artifacts, and shortcuts that do not generalize to clinical settings. Results from this project must not be used to make medical decisions.
