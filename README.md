# How Do LLMs Encode Scientific Quality? An Empirical Study Using Monosemantic Features from Sparse Autoencoders.

## Abstract:
In recent years, there has been a growing use of generative AI, and large language models (LLMs) in particular, to
support both the assessment and generation of scientific work. Although some studies have shown that LLMs
can, to a certain extent, evaluate research according to perceived quality, our understanding of the internal
mechanisms that enable this capability remains limited. This paper presents the first study that investigates
how LLMs encode the concept of scientific quality through relevant monosemantic features extracted using
sparse autoencoders. We derive such features under different experimental settings and assess their ability to
serve as predictors across three tasks related to research quality: predicting citation count, journal SJR, and
journal H-index. The results indicate that LLMs encode features associated with multiple dimensions of scientific
quality. In particular, we identify four recurring types of features that capture key aspects of how research
quality is represented: 1) features reflecting research methodologies; 2) features related to publication type, with
literature reviews typically exhibiting higher impact; 3) features associated with high-impact research fields and
technologies; and 4) features corresponding to scientific jargon. These findings represent an important step
toward understanding how LLMs encapsulate concepts related to research quality.

## Repository Structure:
This repository contains relevant files associated with the paper listed above.

Here is an overview of the key directories:

- BERT_details/: This directory contains a text file indicating what model was used, what tokenizer was used, the parameters used in training the model.

- confusion_matrices/: Stores the visualizations of confusion matrices, for each task and LLM & SAE combination.

- datasets/: Contains the dataset used in the project. This dataset details the title, abstract, research quality metrics, and other details. 

- decision_trees/: Holds the decision tree visualizations which are generated to explain the features.

- monosemantic_feature_descriptions/: has a csv document detailing the definitions of each monosemantic feature used by each decision tree yeild from each task and LLM & SAE combination.

- prompts/: Stores the text prompts that the language models used in this analysis.