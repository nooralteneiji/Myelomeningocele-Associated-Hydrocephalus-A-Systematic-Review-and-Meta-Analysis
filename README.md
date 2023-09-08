# **Management and Outcomes of Myelomeningocele-Associated Hydrocephalus in Low-Income and Middle-Income Countries: A Systematic Review and Meta-Analysis**

[![Binder](https://mybinder.org/badge_logo.svg)]( )
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/github/matteomancini/myelin-meta-analysis/blob/master/meta-analysis.ipynb](https://colab.research.google.com/drive/1OrB85UySxAv3lPb05gjNAmFI5b5hsO6M?usp=sharing))

<br>

This repository houses a systematic review and meta-analysis focusing on the management and outcomes of myelomeningocele-associated hydrocephalus in low-income and middle-income countries. Through an extensive evaluation of relevant studies, the analysis aims to understand the landscape of treatments, interventions, and outcomes in diverse economic environments. 

The core of the repository is a [Jupyter notebook](https://github.com/nooralteneiji/Clinical-outcome-in-degenerative-cervical-myelopathy--a-systematic-review/blob/main/Interactive_manuscript.ipynb), structured to guide readers through the entire process, from data setup to the presentation of findings in detailed tables and visualizations. Supplementary materials provide additional insights. 

The repository was inspired by Matteo Mancini's [meta-analysis of MRI biomarkers of myelin](https://github.com/matteomancini/myelin-meta-analysis/tree/master). 

This repository offers valuable insights into the challenges and patterns of treating myelomeningocele-associated hydrocephalus across different economic contexts.

## Pre-requisites 
To execute the notebook, ensure you have Python (version 3.11.4), Jupyter, and the R packages ['metafor'](http://www.metafor-project.org) and 'multcomp' installed. The mixed-effect model is implemented using the 'metafor' package, which is interfaced through the ['rpy2'](https://rpy2.github.io) package. For more details, refer to the [metafor project](http://www.metafor-project.org) and [rpy2 documentation](https://rpy2.github.io).

## **Contents:**
1. **Setup**: Environment setup, including the import of necessary libraries and loading of primary datasets.
2. **PRISMA Diagram**: A visual representation of the studies included and excluded during the review process.
3. **Tables and Figures**: Detailed tables and figures that provide a comprehensive overview of studies and their findings.
4. **Supplemental Materials**: Additional insights, including a list of studies excluded at the full-text screening stage and their reasons.

## **Usage:**
The cells do not need to be loaded sequentially to reproduce the results and visualizations, as long as you first run the 'Set-up' code block found at the start of the script.

## **Datasets:**
The [primary dataset](https://github.com/nooralteneiji/Clinical-outcome-in-degenerative-cervical-myelopathy--a-systematic-review/blob/main/Data.xlsx) is organized into multiple sheets, each representing different facets of the study. Each sheet is loaded into its respective DataFrame for analysis.

## **License:**
