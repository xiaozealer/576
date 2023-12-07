# Intent Analysis Project

This repository contains the Jupyter notebooks for the experiments conducted in our intent analysis project. Each notebook corresponds to a specific part of the research, detailing the methodology, implementation, and results of the experiments.

## Project Overview

The goal of this project is to evaluate the performance of different NLP models on the task of intent classification. We investigate the effectiveness of GPT-2 and BERT models and explore how enhancements like additional classification heads can improve model performance.

## Repository Structure

The repository is structured as follows:

- `gpt-baseline-intent_analysis_model.ipynb`: This notebook presents the baseline experiment using the GPT-2 model with an intent classification head.
- `gpt-improved-intent_analysis.ipynb`: This notebook documents the improvements made to the baseline GPT-2 model, including the implementation of a scenario head.
- `bert-intent_analysis.ipynb`: This notebook details the experiments conducted with the BERT model, showcasing its performance on the same intent classification task.

Each notebook contains a mixture of markdown explanations, code cells, and visualizations that collectively present our findings.

## How to Use

To run these notebooks and replicate our experiments, follow these steps:

1. Clone the repository to your local machine or open it in a Jupyter environment.
2. Ensure you have all the required dependencies installed. A list of dependencies can be found in the `requirements.txt` file.
3. Open each Jupyter notebook and execute the cells in order to observe the experiments and results.


## Results

The notebooks include detailed performance metrics such as F-1 Score and Test Accuracy. For a comprehensive discussion of the results, please refer to the `intent_analysis_report.pdf`.

