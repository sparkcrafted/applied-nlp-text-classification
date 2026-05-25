# Applied NLP Text Classification

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-Natural%20Language%20Processing-154f3c?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

## Overview

This project is an applied natural language processing case study focused on text classification, sentiment analysis, emotion modeling, and exploratory analysis of unstructured text.

The project demonstrates how text data can be cleaned, transformed, modeled, and interpreted for decision-support purposes. Rather than treating natural language processing as a purely technical exercise, this case study frames NLP as a practical tool for organizations that need to understand large volumes of text more efficiently.

The project was developed as part of a broader applied analytics portfolio focused on management science, business problem-solving, data preparation, modeling, and decision support.

## Business Problem

Organizations often collect large volumes of unstructured text through reviews, surveys, customer feedback, social platforms, help desk systems, reports, documents, and other communication channels. This information may contain useful signals about sentiment, experience, risk, satisfaction, dissatisfaction, urgency, or recurring themes.

However, manually reviewing text at scale can be slow, inconsistent, and difficult to operationalize.

A management, operations, or analytics team may need a repeatable way to:

- classify text into meaningful categories;
- identify sentiment or emotional signals;
- detect patterns in language;
- compare model performance;
- reduce manual review time;
- convert unstructured text into structured decision-support data.

## Project Objective

The objective of this project is to build and evaluate NLP workflows that classify and analyze text using machine learning methods.

The analysis focuses on:

- preparing raw text for modeling;
- converting text into numerical features;
- training classification models;
- evaluating model performance;
- comparing NLP workflows across different text datasets;
- interpreting results in a business and decision-support context.

## Project Workflows

This repository includes multiple applied NLP workflows.

| Workflow | Dataset | Purpose |
|---|---|---|
| Sentiment classification | `movie_data.csv` | Classifies review text by sentiment and evaluates model performance. |
| Emotion classification | `train.txt`, `val.txt`, `test.txt` | Models emotion labels from text data using training, validation, and test splits. |
| Caption text analysis | `image_caption.txt` | Supports text preprocessing and exploratory NLP analysis using caption-style text. |

## Methods

This project uses a standard applied NLP and text classification workflow:

1. **Data review and preparation**
   - Load and inspect text datasets.
   - Review text fields, labels, and dataset structure.
   - Prepare data for analysis and modeling.

2. **Text preprocessing**
   - Clean and standardize text.
   - Remove unnecessary characters and noise.
   - Prepare raw text for feature extraction.

3. **Feature engineering**
   - Convert text into model-ready features.
   - Use vectorization techniques such as TF-IDF to represent language numerically.

4. **Model development**
   - Train classification models to predict sentiment or emotion labels.
   - Compare model performance using common evaluation metrics.

5. **Model evaluation**
   - Review accuracy and classification performance.
   - Use confusion matrices and related metrics to understand model strengths and limitations.

6. **Decision-support interpretation**
   - Translate technical outputs into practical implications for analytics, operations, and organizational decision-making.

## Tools and Technologies

| Category | Tools |
|---|---|
| Programming | Python |
| Notebook environment | Jupyter Notebook |
| Data manipulation | pandas, NumPy |
| NLP / text processing | NLTK, TF-IDF vectorization |
| Machine learning | scikit-learn |
| Visualization | Matplotlib |
| Output format | Jupyter Notebook, markdown documentation |

## Repository Structure

```text
applied-nlp-text-classification/
  README.md
  notebook/
    applied_nlp_text_classification.ipynb
  data/
    raw/
      movie_data.csv
      image_caption.txt
      emotions/
        train.txt
        val.txt
        test.txt
    README.md
  images/
    confusion_matrix.png
    model_comparison.png
    top_terms.png
    sentiment_distribution.png
  docs/
    project_summary.md
  requirements.txt
  .gitignore
  LICENSE
