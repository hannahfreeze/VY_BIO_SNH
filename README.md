README – Vineyard Biodiversity MSc Analysis

Project Overview

This folder contains data and R scripts for Hannah Friesen's MSc project on vineyard biodiversity in the Okanagan Valley, BC. The research investigates:

How ground-dwelling arthropods (carabid beetles and spiders) abundance and richness vary across vineyard and semi-natural habitats.

**Folder Structure**

**00_data/**

Cleaned datasets used in analyses.

Includes:

-   spider_habitat_df.csv
-   carabid_habitat_df.csv
-   spider_family_traits.csv
-   carabid_traits.csv

A complete description of all datasets and variables is provided in data_dictionary.csv.

**01_analysis/**

R Markdown containing integrated workflows for data wrangling, visualization, and statistical analyses.

Includes:

-   habitat_analysis.rmd (Rmarkdown)
-   habitat_analysis.html (knitted html file)
-   grateful-refs (references for packages)

**02_tables/**

Processed output tables used in the thesis and manuscripts.

Example:

\- carabid_hill_diversity.csv

**03_figures/**

Figures generated from Rmarkdown.

Example:

\- carabid_genus_relative_abundance.png

**04_manuscript/**

Manuscript-related files, including pre-registration materials and draft or final papers.

**Data Description**

Arthropods were sampled using pitfall traps placed along transects in vineyards and adjacent semi-natural habitats at 14 sites in 2024 and 31 sites in 2025 in the Okanagan Valley, British Columbia.

Sampling occurred during June and September in 2024, and June in 2025. September 2024 data were excluded from analyses due to inconsistent trap deployment and incomplete site coverage, which limited comparability across sites and years.

Spider specimens were identified to the family level, and carabid beetles to the species level

Functional trait datasets include information on spider foraging guilds and carabid dispersal ability and biogeographic status.

A detailed data dictionary describing all variables, units, and codes is provided in data_dictionary.csv.

**Software & Dependencies**

All analyses were conducted in R (≥4.5.2).

**Main packages:**

tidyverse (data wrangling, plotting)

gllvm (generalized linear latent variable models)

iNEXT (hill diversity)

ggplot2 (figures)

Scripts include library() calls for required packages.

**Reproducibility**

All results, tables, and figures can be reproduced by running the R Markdown files in the 01_analysis/ directory.

**Notes**

-   Vineyard locations/ coordinates are not included to protect vineyard privacy
-   Dataset and variable names are consistent across files to facilitate merging and reuse.
-   Some habitat categories were aggregated or excluded during analysis (e.g., crop row and drive row combined into vineyard habitat; field margins excluded). These decisions are documented in the data dictionary and analysis scripts.

This repository is intended for academic and research use.

**Contact**

For questions about this analysis, contact:

MSc Candidate: Hannah Friesen ([hannah.friesen\@live.ca](mailto:hannah.friesen@live.ca){.email})

Supervisors: Dr. Kirsten Hannam (AAFC), Dr. Lael Parrott (UBCO)

Committee members: Dr. Dave Ensing (AAFC), Dr. Jason Pither (UBCO)
