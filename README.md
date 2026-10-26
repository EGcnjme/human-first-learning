# Human-first learning: analysis code

This repository contains the R code for the statistical analyses reported in the manuscript *"Human-first learning: scaffolding reasoning before AI assistance improves diagnostic accuracy"*.

## Files

| File | Description |
|---|---|
| `GLMM_P1-P4.Rmd` | Analysis for RQ1: generalized linear mixed-effects models (GLMM) of diagnostic accuracy across Phases 1–4 |
| `repeated_Anova_4Phase.Rmd` | Analysis for RQ2: repeated-measures ANOVA across the four phases |

## Data

The de-identified dataset is available on figshare: https://doi.org/10.6084/m9.figshare.34628382

Download the dataset from figshare and place it in the **same directory** as the `.Rmd` files before running the code.

Note: The DOI will become active upon publication of the manuscript.

## Requirements

- R (version 4.5.2)
- lme4 (version 2.0.1)

## Usage

1. Download the data from figshare and place it in the same folder as the `.Rmd` files.
2. Open the `.Rmd` file in RStudio.
3. Click **Knit**, or run the chunks one by one.

## License

The code is released under the MIT License. The data are released under CC BY 4.0 (see figshare).
