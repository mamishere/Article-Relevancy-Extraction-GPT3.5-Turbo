# Enhancing Title and Abstract Screening for Systematic Reviews with GPT-3.5 Turbo

## Project Overview

This project is based on the paper [*Enhancing title and abstract screening for systematic reviews with GPT-3.5 turbo*](https://doi.org/10.1136/bmjebm-2023-112678), published in *BMJ Evidence-Based Medicine* in February 2024. The repository includes the data and the implementation code used in the study to evaluate the performance of GPT-3.5 Turbo in automating the title and abstract screening process for systematic reviews (SRs).

Systematic reviews require precise and accurate screening of titles and abstracts, a task that is typically labor-intensive and time-consuming. This project explores how GPT-3.5 Turbo, a large language model, can assist in this process by reducing the workload on researchers while maintaining high levels of accuracy.

## Repository Structure

- **Relevancy Extraction Notebook.ipynb**: This Jupyter notebook contains the complete implementation of the relevancy extraction process as described in the paper. It includes steps for data preprocessing, prompt engineering for GPT-3.5, and the evaluation of the model's performance.
  
- **Data**: Contains the dataset used for the study, including titles, abstracts, and metadata of research papers related to "Light Therapy in Insomnia Disorder."

- **Scripts**: Any additional Python scripts used in the project are stored here.

## Methodology

### Data Collection

The dataset was derived from a systematic review titled "Light Therapy in Insomnia Disorder: A Systematic Review and Meta-Analysis." The dataset includes titles, abstracts, and metadata, which were structured for use with GPT-3.5 Turbo.

### Prompt Engineering

The project developed a series of prompts to test different levels of specificity and inclusivity in guiding GPT-3.5 Turbo during the screening process. These prompts were designed to explore the model's ability to accurately replicate human screening decisions.

### Model Evaluation

The performance of GPT-3.5 Turbo was compared with that of human researchers using metrics such as sensitivity, specificity, accuracy, and F1 scores. The results demonstrated that detailed and specific prompts yield better screening performance.

## Results

The study found that while GPT-3.5 Turbo is a valuable tool for assisting in title and abstract screening, it is not yet a replacement for human screeners. The model is particularly effective when guided by well-crafted prompts but should be used in conjunction with human judgment to ensure comprehensive results.


