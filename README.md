# eCSM-projections — Analysis code

Analysis code for:

Maurud S, Lunde L, Moen A, Opheim R. Patient profiles of self-management
priorities for focused health service support in inflammatory bowel disease.
Under review.

## Contents

- `eCSMprojections.Rmd` — full analysis workflow: text preprocessing, topic modelling, PCA, hierarchical clustering profile identification 
- `eCSMprojections.pdf` — rendered version of the above

## Data availability

The underlying patient data were analysed within the University of Oslo's
Services for Sensitive Data (TSD) and are not publicly available due to
privacy regulations and the terms of the ethics approval. The code is shared
to document the analytical workflow.

## Software and packages

Analyses were conducted in R (version 4.4.1) with Python (3.12.6)
integrated via `reticulate`.

### Python libraries

| Library | Purpose |
|---|---|
| NLTK | Processing text |
| pandas | Creating and processing data frames |
| NumPy | Creating and processing matrices |
| scikit-learn | Topic modelling |
| Gensim | Computing topic model coherence (C_v) |

### R packages

| Package | Purpose |
|---|---|
| reticulate | Python integration in R |
| dplyr, tidyr | Data wrangling and processing |
| cluster | Agglomerative clustering and silhouette coefficient |
| proxy | Computing cosine distance |
| fpc | Bootstrapped Jaccard similarity index |
| eq5d | EQ index for the Norwegian value set |
| coin | Fisher–Pitman permutation tests |
| rstatix | Asymptotic Z-tests of significant chi-squared tests |
| ggplot2, grafify | Visualising findings |
