# Kaggle Competition: [WSDM-Cup](https://www.kaggle.com/competitions/wsdm-cup-multilingual-chatbot-arena/overview)

## Overview
This repository contains a Jupyter Notebook developed for the WSDM Cup hosted on Kaggle. The goal of this competition was to implement a model, which predicts which of the two LLM answers will a person choose. Dataset consisted of prompts, two answers, names of the models, language and winner — model A or model B, which was choosen for a better answer.

## Methodology
- **Preprocessing:** EDA (e.g. language distribution, lengths of prompts and responses, frequencies of winning), extracting numerical features from text columns.
- **Modeling:** logreg and finetuning of a XLM-RoBERTa.
- **Evaluation:** logloss and accuracy.

## Results
- **New techniques:** LLM finetuning, LoRA, QLoRa
- **Best score:** accuracy = 0.6399 (accuracy of the winner = 0.712)

Unfortunately, I have not submitted any notebooks as my main goal was to try, not to get a medal. Anyway, it was an interesting experience and, I guess, only the beginning of my way of participating in Kaggle competitions.
