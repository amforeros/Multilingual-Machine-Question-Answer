# Multilingual-Machine-Question-Answer
In this project, we developed a multilingual question-answering system for the Natural Language Processing at the University of Copenhagen group project. We use a public dataset (TyDi QA) that contains unanswerable questions (https://huggingface.co/datasets/copenlu/answerable_tydiqa). We show how artificial intelligence works in answering questions for documents in Arabic, Bengali and Indonesian. The project was developed in seven weeks, each containing different challenges as described below:
Multilingual QA Project Overview
This repository documents a comprehensive approach to tackling multilingual question answering (QA) tasks using a structured, week-by-week methodology. The project spans six weeks and focuses on three languages—Arabic, Bengali, and Indonesian—addressing both binary classification and span-based QA tasks.

## Week 36: Dataset Exploration and Basic Data Analysis
- Familiarized with the dataset, downloaded and explored the columns.
- Summarized key data statistics for the training and validation sets in all three languages.
- Extracted and analyzed the five most common words in both the documents and questions for each language, identifying patterns and key insights.
## Week 37: Language Model Implementation
- Developed language models separately for the documents and questions in Arabic, Bengali, and Indonesian.
- Implemented and evaluated three distinct models for each language, comparing their performance across different validation sets.
## Week 38: Supervised Classifier Training
- Built supervised classifiers using features such as bag-of-words, n-gram counts, word embeddings, and neural language models.
- Trained and evaluated these classifiers on the respective validation sets for each language, analyzing and comparing their performance across languages.
## Week 39: Sequence Labeling for Span-based QA
- Transitioned from binary classification to span-based QA.
- Implemented three sequence labelers per language to predict which tokens in a document form the answer to a given question.
- Evaluated and compared the performance across the languages.
## Week 40: Transformer-Based Model Visualization
- Selected and implemented a Transformer-based model for both binary classification and sequence labeling.
- Visualized the model's attention layers for selected validation instances in each language, aiming to explain the predictions.
## Week 41: Cross-Lingual Evaluation
- Performed zero-shot cross-lingual evaluation by training models on one language and testing on the others.
- Analyzed the results to determine which language serves as the most beneficial for training and cross-lingual generalization.


This project serves as a deep dive into multilingual QA, showcasing diverse methodologies from basic statistical analysis to advanced Transformer-based models. Feel free to explore the code, models, and results documented in this repository!
