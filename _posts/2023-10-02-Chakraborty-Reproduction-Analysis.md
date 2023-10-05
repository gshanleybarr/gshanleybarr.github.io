---
title: "Reflections on Conducting A Reproduction Analysis"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Reproduction
  - Reanalysis
  - Lessons learned

---
[Reproduction of Chakraborty 2021: An intracategorical analysis of COVID-19 and people with disabilities](https://gshanleybarr.github.io/RPr-Chakraborty-2021/)


The process of conducting a [reanalysis](https://gshanleybarr.github.io/RPr-Chakraborty-2021/) of [Chakraborty’s (2021)](10.1016/j.dhjo.2020.101007) study has taught me the importance of clear methodology, particularly in regard to data acquisition, cleaning, analysis, and visualization. While communicating research results in an accessible format for diverse audiences is critical to ensure the dissemination of results, it is simultaneously just as important to document research methods to ensure that future researchers can build upon scientific knowledge and test the validity of methods and findings. One means to make science more transparent is through clear documentation of source code, data sources, and analytical methods, particularly if the analysis and documentation occur on open source platforms. Working in an open source environment can assist in fostering an environment of communal scientific production, where scientific legitimacy comes from knowledge being tested by peers in a scientific community.

In working on  a reanalysis of Chakraborty’s (2021) I contributed most substantially to editing data visualization of maps to improve the cohesion and more effectively convey results of the report. For example, I added a series of five maps that compare the geographic distribution of people with disabilities by race. In addition, I assisted with data table formatting, restructuring the discussion, adding a section on areas for improvement in the study design, and adding a conclusion to the reproduction analysis manuscript.

The reproduction analysis intentionally deviated slightly from the original study in order to conduct robustness tests on the results of the original analysis and to use an Open Source computational environment (R Studio). In addition to these planned deviations in the reproduction analysis, there were a handful of deviations from the original analysis in the reproduction, including: the calculation of bivariate tests, results comparing SaTScan and SpatialEpi Packages, mapping disability rates, and  missing data errors. Additional details on the deviations can be found in an appendix below. In sum, working on this reproduction demonstrated the challenges of conducting a reproduction analysis even when the original data and methods were available. Findings from this experience highlight the importance of ensuring that scientific research is done in an equitable and reproducible manner to ensure the validity of findings. 
