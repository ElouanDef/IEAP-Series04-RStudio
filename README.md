# IEAP Series 04 – RStudio Assignment

## Overview

This repository contains our team's submission for the IEAP Series 04 assignment. The project demonstrates statistical modeling, data wrangling, and Git version control best practices using R and Quarto.

## Project Structure

To facilitate parallel development and avoid merge conflicts, we utilized a modular Quarto architecture: \* `IEAP-Series04-RStudio.qmd`: The master Quarto document that aggregates the project. \* `sections/`: Contains the child documents (`.qmd`) for each specific part of the assignment. \* `data/`: Contains the raw physiological datasets (`.zip` files) used for the analysis. \* `references.bib`: The APA bibliography database.

## Key Analyses

- **Part 2 - Linear Regression & Random Noise:** Simulating the impact of varying noise levels on linear model parameter estimation, prediction accuracy, and explained variance.
- **Part 3 - Heart Rate Recovery:** Comparing linear, mono-exponential, and bi-exponential models (`nls`) to evaluate post-exercise heart rate recovery using aligned triaxial accelerometer and pulse data.
- **Part 4 - Git Workflow:** A breakdown of our team's branching strategy, modular architecture, and the technical challenges we resolved to maintain a clean repository.

## Rendering the Document

This project is explicitly configured to output GitHub-Flavored Markdown (`gfm`) with native APA citations. To fully compile the document and generate the figure assets from scratch, run the following command in the RStudio Terminal:

``` bash
quarto render IEAP-Series04-RStudio.qmd --execute
```

## Authors

- Werner Binche
- Elouan Delfin
- Vidusha Thebuwana
