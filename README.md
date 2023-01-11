# explainability_data
We present data used for experiments in the manuscript: "Explaining Poor Performance of Text-Based Machine Learning Models for Vulnerability Detection" by Kollin Napier, Dr. Tanmay Bhowmik, and Dr. Zhiqian Chen (Napier et al.).

This repository contains two archived (zipped) folders containing data related to the projects and Common Weakness Enumeration (CWE) vulnerability data. This data is a modification from data utilizied from the empirical study: "An Empirical Study of Text-based Machine Learning Models for Vulnerability Detection" by Kollin Napier, Dr. Tanmay Bhowmik, and Dr. Shaowei Wang (Napier et al.) [1].

The data corresponds to the data processing methods introduced in the prior empirical work. Such methods are: Full Context (FC) and No Context (NC).

This work explores the removal of overlapping features from the training and testing data, deemed "cross-cutting" features. We present two scenarios in which such features are removed from the data. Scenario 1 (S1): "cross-cutting" features are removed from the training data only. Scenario 2 (S2): "cross-cutting" features are removed from the training and testing data.

The `projects_data` folder contains the top 10 projects as defined from prior work. Data used for our study is included.

The `cwe_data` folder contains the top 10 CWE vulnerability types as defined from prior work. Data used for our study is included.

[1] https://github.com/krn65/emse_data
