# roBERTa-Symptom-Tracking
Using roBERTa symptom tracking (using NER) to find out what are the most common symptoms before and after COVID-19 in medical interviews.

This is a project for the course 'Natural Language and Dialogue Processing' in the bachelor Artificial Intelligence (University of Amsterdam). 

## Data
I will be using the following datasets:
- COVID-19 Dialogue Datase (during/after covid) https://www.kaggle.com/xuehaihe/covid-dialogue-dataset?select=COVID-Dialogue-Dataset-English.txt
- MedDialog Dataset (English) (before covid)  https://github.com/UCSD-AI4H/Medical-Dialogue-System

## roBERTa
I will be using a pre-trained XLM-roBERTa model from huggingface (https://huggingface.co/asahi417/tner-xlm-roberta-base-bc5cdr). The model is finetuned on NER (https://github.com/asahi417/tner) on the BC5CDR dataset, which consists of 1500 PubMed articles with 4409 annotated chemicals, 5818 diseases and 3116 chemical-disease interactions.

TODO: explain workings of roBERTa :) 

## Pipeline
- Find a pre-trained roBERTa on medical dialogue data
- Use pre-trained roBERTa to extract symptoms from medical dialogue before and after COVID-19
- Display most common symtoms 
- Model evaluation 


