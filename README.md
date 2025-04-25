# 690UBio-Informatics-Course-Project
690U: Bio Informatics Course Project: EC Classification of Proteins: Comparing Lightweight Models to Foundation Models

# Diverse Genome Embedding Benchmark




Declaration of Intent: \

Basic Idea:
Compare a simple model with a complex model from the DGEB paper in case of EC-Classification -> do we really need a complex foundation model?

Using AA (amino acids)

---

I will test or plot: \

The performance (e.g., F1-score) of a logistic regression model trained on one-hot encoded protein sequences for EC number prediction. I will also compare this performance to published results from foundation models in the DGEB benchmark.

If the hypothesis is true, I will observe: \

The logistic regression model will achieve comparable performance (in terms of F1-score) to the foundation model baseline on the EC Classification task, indicating that simple models can be effective with basic encodings.

If the hypothesis is false, I will observe: 

The logistic regression model will perform significantly worse than the foundation models, suggesting that the complex, pre-trained representations are capturing important functional features that simple models miss.

### Idea:
#### Getting TSV -> Do One-Hot-Encoding -> Split -> train Modell -> test Model -> comapare Results with DGEB -> discussion
