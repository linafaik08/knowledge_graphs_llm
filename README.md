# Knowledge Graphs & LLM

- Author: [Lina Faik](https://www.linkedin.com/in/lina-faik/)
- Creation date: August 2024
- Last update: August 2022

## Objective

This repository contains the code and notebooks used in the article on building knowledge graphs and leveraging them for LLM queries, utilizing the Llama-Index library. For more information, you can find the articles here:

[From Text to Networks: The Revolutionary Impact of LLMs on Knowledge Graphs](https://medium.com/@linafaik)   
Practical Application to Customer Churn Prediction

<div class="alert alert-block alert-info"> You can find all my technical blog posts <a href = https://linafaik.medium.com/>here</a>. </div>

## Project Description

### Data

The data used in this repository is sourced from the Wikipedia [page](https://fr.wikipedia.org/wiki/Panama_Papers) on the Panama Papers scandal.


### Code structure

```
data # folder containing the source documents
notebooks # experiments
├── 01_kg_extraction.ipynb 
├── 02_kg_querying.ipynb
outputs # experiments results
config.py
requirements.txt
README.md
```

## How to Use This Repository?

### Requirement

The code relies on the following libraries:

```
pyvis==0.3.2
llama_index==0.10.65
```

### Experiments

To run experiments, you need to run the notebooks in the order suggested by their names. 