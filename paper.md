---
title: 'StateLevelForest: An R package containing a century of U.S. forest dynamics'
tags:
- forest
- public data
- united states of america
- conservation
- preservation
date: "22 November 2023"
output: pdf_document
authors:
- name: Gates Dupont
  corresponding: yes
  orcid: "0000-0003-1175-0694"
  affiliation: 1
- name: Andy Dobson
  orcid: "0000-0002-9678-1694"
  affiliation: 1, 2, 3
bibliography: paper.bib
affiliations:
- name: "Department of Ecology and Evolutionary Biology, Princeton University, Princeton,
    NJ, 08544, USA""
  index: 1
- name: "Santa Fe Institute, Santa Fe, NM, 87501, USA"
  index: 2
- name: "Smithsonian Tropical Research Institute, Panama City, 0843-03092, Panama"
  index: 3
---

# Summary

The `StateLevelForest` package provides an important dataset environmentally related research, encapsulating over a century's worth of forest cover data across the United States. This dataset, spanning from 1907 to 2017 (with 1630 as a reference), provides a unique perspective on the historical changes in the total extent of forest areas in each U.S. state, allowing researchers to track and analyze trends in deforestation and reforestation at broad spatiotemporal scales. Forests play critical roles in carbon sequestration, climate regulation, and biodiversity maintenance, and understanding these changes can be critical, and the `StateLevelForest` dataset is highly valuable to inforum research endeavors on these topics. Improving access to this dataset will create new opporunities for ecologists, environmental scientists, policy makers, and educators, offering data essential to understand the history of forests in the U.S. to contextualize recent patterns. The package simplifies access to this extensive dataset within the R environment, facilitating its integration into research workflows and data analysis pipelines.

# Statement of need

`StateLevelForest` [@Dupont] is an R package designed to provide greatly improved access to a comprehensive dataset of state-level forest cover in the United States (see @Oswalt). This dataset is critical for a wide range of applications, from academic research in environmental science and ecology to policy formulation and educational purposes. Given the increasing awareness and concern over environmental changes and resulting global impacts, such a dataset is indispensable for longitudinal studies and decision-making processes related to forest management and conservation efforts.

The package's primary aim is to offer a user-friendly interface to access and work with historical forest data. It addresses the need for a standardized and reliable source of historical forest cover information in the U.S., which has been relatively inaccessible in existing resources. Using the data in `StateLevelForest`, users can easily perform analyses and create visualizations (see \autoref{fig:states}) to derive insights into the dynamics of forest cover changes over a span of over a century. Its integration into the R environment, a platform widely used in statistical and environmental data analysis, ensures that the package can be seamlessly used with the latest analytical tools.

`StateLevelForest` is particularly timely and relevant given the current environmental challenges and the need for data-driven approaches to understand and mitigate the impacts of the climate and biodiversity crises. It is poised to support a range of scientific inquiries and publications, as well as to enhance educational materials with empirical data, thereby bridging the gap between historical data availability and contemporary environmental research needs.

# Availability

The package is available on [CRAN](https://cran.r-project.org/web/packages/StateLevelForest/index.html) and also available at the GitHub repository: [https://github.com/GatesDupont/StateLevelForest](https://github.com/GatesDupont/StateLevelForest)

Upon opening R, a user can access the data with just a few lines of code:
```{r}

# Install the packages
# install.packages("StateLevelForest") # un-comment you are installing for the first time

# Load the package
library(StateLevelForest)

# Load the data frame into your Workspace
data(StateLevelForest)

```


# Figures

![State-level Forest Cover Trends in the United States from 1907 to 2017. Each panel represents a U.S. state and displays the forest area in thousands of acres over the observed period. The red line indicates the 1630 reference level, serving as a baseline for comparison. The data visualized encapsulates the significant fluctuations in forest coverage, highlighting instances of deforestation and reforestation. These visual trends provide a macroscopic view of the historical and contemporary states of forest ecosystems, which are critical for understanding the environmental impact and guiding conservation efforts.\label{fig:states}](figure.png)

# Acknowledgements

We acknowledge all those involved in collecting and curating these data at the U.S. Census Bureau and U.S. Forest Service (USFS) and beyond over the last 100+ years. This was surely an immense effort. We thank USFS, in particular, for making the dataset publicly available in their above-mentioned report. We thank CRAN and its team members for hosting the R package we describe here, and we thank the reviewers of their helpful feedback.

# References
