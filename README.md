# How many do we miss? - Evaluation of age at onset and family history as selection criteria for genetic testing in Parkinson‘s disease

<div align="center">
    <a href="https://gp2.org/">
    <img src="https://www.michaeljfox.org/sites/default/files/styles/grant_image_opportunity_detail/public/grant/GP2%20Logo.png?itok=OhZkYS-H" alt="GP2 Logo" width="200">
</a>
</div>


`GP2 ❤️ Open Science 😍`
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/nnnnn.svg)](https://doi.org/nnnn/zenodo.nnnnn)


**Last Updated:** November 2025

## Summary
This repository contains the code and workflow used in the study:
**“How many do we miss? - Evaluation of age at onset and family history as selection criteria for genetic testing in Parkinson‘s disease”.**

## Data Statement
* The data was obtained from the Global Parkinson’s Genetics Program (GP2) release 9 (GP2 release 9, DOI: 10.5281/zenodo.14510099) and access can be requested through the Accelerating Medicines Partnership in Parkinson’s Disease (AMP-PD) via the online application process (https://www.amp-pd.org/).

## Citation
[*DOI: pending publication*]

### Helpful Links 
- [GP2 Website](https://gp2.org/)
    - [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
- [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
    - [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)

## Repository Orientation
* The `analyses/` directory includes the .Rmd script discussed in the manuscript.
* Data extraction from the GP2 was performed using notebooks described previously in the code accompanying "Exploring the Global Landscape of Rare Causal and Common High-Risk Variants in Parkinson’s Disease" manuscript (https://github.com/GP2code/GP2-global-genetic-variant-landscape). 

```
THIS REPO
├── GenTestGP2_clean.Rmd
├── LICENSE
└── README.md
```

## Analyses

- Languages: R

| **Notebook**                   | **Description**                                                                                                                                                         |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 00_GenTestGP2_clean.Rmd | Data analysis and plotting|


## Software

| **Software** | **Version(s)** | **Resource URL** | **RRID** | **Notes** |
|--------------|----------------|------------------|----------|-----------|
|R Project for Statistical Computing|v.4.2.2|http://www.r-project.org/|RRID:SCR_001905| pROC, readxl, knitr, gdata, DescTools, openxlsx ; Used for general data wrangling/plotting/analyses	|
