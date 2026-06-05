# LLM Synthetic Data for Stance Detection

## Project Overview

This project investigates the effectiveness of Large Language Model (LLM) generated synthetic data for stance detection tasks in both Arabic and English.

The study evaluates whether synthetic datasets generated using ChatGPT and Falcon can improve the performance of stance detection models when compared with real-world datasets.

This work was conducted as part of my MSc in Artificial Intelligence at Cardiff University.

---

## Research Objectives

* Generate synthetic stance detection datasets using LLMs.
* Compare synthetic and real datasets.
* Evaluate the effectiveness of synthetic data augmentation.
* Assess model performance across Arabic and English datasets.
* Analyze bias, limitations, and language-specific challenges.

---

## Datasets

### English Datasets

* Feminist Movement
* COVID-19 Vaccine

### Arabic Dataset

* Women's Empowerment

Both real and synthetic datasets were used throughout the experiments.

---

## Models Evaluated

### English Models

* RoBERTa
* DistilBERT

### Arabic Models

* AraBERT

---

## Synthetic Data Generation

Synthetic datasets were generated using:

* ChatGPT
* Falcon

Prompt engineering techniques and topic modeling were applied to improve data quality and diversity.

---

## Methodology

1. Data preprocessing
2. Topic modeling
3. Synthetic data generation
4. Model fine-tuning
5. Performance evaluation
6. Comparative analysis

---

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Scikit-learn
* Pandas
* NumPy
* Jupyter Notebook

---

## Key Outcomes

* Generated over 5,000 synthetic Arabic and English text samples.
* Evaluated RoBERTa, DistilBERT, and AraBERT models.
* Compared synthetic-only, real-only, and combined training strategies.
* Identified performance gaps and language-specific challenges in Arabic NLP tasks.

---

## Repository Structure

```text
datasets/
notebooks/
prompts/
images/
```

---

## Author

Alhanouf Alsemairi

MSc Artificial Intelligence, Cardiff University

Research Interests:

* NLP
* Large Language Models (LLMs)
* Responsible AI
* AI Governance
* Arabic NLP
