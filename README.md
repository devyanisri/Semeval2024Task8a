# SemEval-2024 Task 8: Multigenerator Multidomain and Multilingual Black-Box Machine-Generated Text Detection

## Overview

This repository contains the work and findings of Annanya Jain, Devyani Srivastava, and Siva Naga Santosh Adabala from the University of Colorado Boulder, focusing on Subtask A of SemEval-2024 Task 8. The task aims to discern between human-authored and AI-generated texts, a crucial skill in today's digital information age. Our work predominantly addresses monolingual tracks in English, reflecting the global data's diverse linguistic landscape.

## Introduction

The proliferation of AI-driven text generation tools has made distinguishing between human and machine-generated content increasingly challenging yet imperative. Our primary focus lies in binary classification, requiring participants to determine whether a given text is human-written or machine-generated. We explore various advanced NLP models and techniques to tackle this challenge, emphasizing the significance of robust text classification systems in an AI-dominated world.

## Methodology

Our approach involves experimenting with state-of-the-art transformer-based models, including DistilBERT, DeBERTa, RoBERTa, and ALBERT, each known for its unique strengths in processing and understanding natural language. We adopted a hybrid methodology, combining different models' components to enhance performance. For example, pairing the DeBERTa tokenizer with the RoBERTa model showcased promising results in accurately classifying texts.

## Experimental Setup

The dataset consists of 119,757 rows, providing a rich and diverse range of textual data for analysis. We detail the preprocessing steps, including text cleaning, tokenization, and normalization, essential for preparing data for model training. Our experimentation phase involved thorough examination of tokenizer and model combinations, leading to the identification of the DeBERTa tokenizer paired with the RoBERTa model as the most effective configuration.

## Results

Our findings are presented through comprehensive analysis and comparative assessments of performance across models. The document (https://github.com/devyanisri/Semeval2024Task8a/blob/main/SemEval_2024Task8a.pdf) includes tables and figures that detail model performance metrics, hyperparameters, and the distribution of training data.

## Conclusion

This project underscores the importance of a systematic and iterative approach to model development and experimentation within the realm of natural language processing. Our experimentation process not only demonstrated the versatility of transformer architectures but also revealed the nuanced dynamics between different components.

## Acknowledgments

We express our heartfelt thanks to Prof. Dr. James Martin for his unwavering support and guidance, which significantly contributed to our successful implementation of learned knowledge in completing this task.

## References

A list of references is provided in the document, offering further reading and resources related to the methodologies and technologies employed in this project.

## Contact

Annanya Jain - anja9719@colorado.edu
Devyani Srivastava - desr8990@colorado.edu
Siva Naga Santosh Adabala - siva.adabala@colorado.edu

## GitHub Repository
[SemEval-2024 Task 8a Repository](https://github.com/devyanisri/Semeval2024Task8a)https://github.com/devyanisri/Semeval2024Task8a
