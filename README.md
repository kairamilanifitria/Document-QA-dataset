# Dataset for Document-based Question Answering

## Overview

This dataset is designed for testing application-based question answering applications or interfaces that accept input in the form of PDF documents. The dataset comprises 20 varied documents, each posing 5 different types of questions, resulting in a total of 100 questions for evaluation. The dataset includes diverse document types, such as journal documents, news articles, financial reports, and tutorials, to assess the QA system's ability to comprehend context, identify keywords, and extract specific information.

## Document Types

1. **Journal Documents (5)**
   - Contain calculations, formulas, and numerical data.

2. **News Documents (5)**
   - Include specific titles and date information.

3. **Report/Financial Report/News Documents (5)**
   - Comprise specific numbers and currency data.

4. **Tutorial Documents (5)**
   - Provide step-by-step instructions in making something, along with numerical information and units.

## Questions and Answers

Each document presents 5 types of questions, and the ground truth serves as the answer key. The questions cover various aspects to assess the QA system's capabilities comprehensively.

## Accuracy Calculation

The accuracy is calculated by determining how many questions are answered with "TRUE" out of the total 100 questions. This metric measures the system's proficiency in extracting accurate information from diverse document types.

## Purpose

The dataset's selection of document variations aims to challenge the QA system to:

- Understand the context of sentences in a document.
- Identify main keywords from diverse document types.
- Extract specific information matching given questions.
- Efficiently sort out relevant information, avoiding overly long answers with minimal accuracy.

## Usage

This dataset provides a robust evaluation tool for application-based question answering systems, allowing developers and researchers to assess their models' performance in handling diverse document types and question types.

## Citation

If you use this dataset in your research or project, please cite it as follows:
