---
title: RefactDataSetValidated
excerpt: "A Manually Validated Code Refactoring Dataset and Its Assessment Regarding Software Maintainability"
layout: repo-dataset
authors: "István Kádár, Péter Hegedűs, Rudolf Ferenc and Tibor Gyimóthy."
version: 4
---

# URL

* [Data Link (DOI)](https://doi.org/10.5281/zenodo.581652)
* [Paper in Digital Library](http://www.inf.u-szeged.hu/~ferenc/papers/RefactDataSet/)

# Change Log

When | What
---- | ----
July 15th, 2016 | Donated by [Rudolf Ferenc](mailto:ferenc@inf.u-szeged.hu)

# Reference

Studies who have been using the data (in any form) are required to include the following reference:

```
@inproceedings{KHFG16_RefactDataSetValidated,
  author = {István Kádár and Péter Hegedűs and Rudolf Ferenc and Tibor Gyimóthy},
  booktitle = {Proceedings of the 12th International Conference on Predictive Models and Data Analytics in Software Engineering},
  pages = {-},
  title = "{A Manually Validated Code Refactoring Dataset and Its Assessment Regarding Software Maintainability}",
  publisher = "ACM",
  year = 2016,
  location = "Ciudad Real, Spain",
}```

# About the Data

## Overview of Data

The dataset contains two types of data for each class and method in a system: static source code metrics and number of refactorings (grouped by types) affecting the particular item between consecutive versions

## Attribute Information

code refactoring, software maintainability, empirical study

## Paper Abstract

Refactoring is a popular technique for improving the internal structure of software systems. It has a solid theoretical background while being used in development practice at the same time. However, we lack empirical research results on the real effect of code refactoring and its ways of application.

This paper presents a manually validated dataset of applied refactorings and source code metrics and maintainability of 7 open-source systems. It is a subset of our previously published dataset containing the refactoring instances automatically extracted by the RefFinder tool. We found that RefFinder had around 27% overall average precision on the subject systems, thus our new - manually validated - subset has substantial added value allowing researchers to perform more accurate empirical investigations.

Using this data, we were able to study whether refactorings were really triggered by poor maintainability of the code, or by other aspects. The results show that source code elements subject to refactorings had significantly lower maintainability values (approximated by source code metric aggregation) than elements not affected by refactorings between two releases.
