# huggingface-nlp-pipeline-lab
Beginner-friendly NLP project using Hugging Face pipelines: sentiment analysis, NER, zero-shot classification, and tokenizer exploration.

## Overview
This project demonstrates fundamental Natural Language Processing (NLP) tasks using the Hugging Face Transformers library. It explores both high-level pipelines and low-level model operations to understand how modern NLP systems work.

## Objectives
- Understand how Hugging Face pipelines simplify NLP workflows
- Explore tokenization and how text is converted into model inputs
- Perform manual model inference using PyTorch
- Compare different NLP tasks such as sentiment analysis, NER, and zero-shot classification

## Project Structure
huggingface-nlp-pipeline-lab/
│
├── README.md
├── requirements.txt
├── Huggingface Transformers.ipynb

## Notebook Contents
The Notebook includes:
- Sentiment analysis using a pretrained pipeline
- Named Entity Recognition using a BERT-based NER model
- Zero-shot text classification
- Tokenizer exploration
- Special tokens such as [CLS] and [SEP]
- Manual model prediction using PyTorch
- Saving and loading pretrained models


## Installation
pip install -r requirements.txt

## Usage
Open the notebook:
  jupyter notebook huggingface_transformers_lab.ipynb
Then run the cells from top to bottom.

## Key Learnings
- Hugging Face pipelines simplify NLP workflows by combining tokenization, model inference, and output formatting.
- Tokenizers convert raw text into numerical input IDs that transformer models can process.
- Attention masks help the model distinguish real tokens from padding.
- Model outputs are often logits, which are raw prediction scores.
- Manual inference helps explain what happens behind the pipeline abstraction.

## Future Improvements
- Add more model comparisons
- Fine-tune a model on a custom dataset
- Explore Retrieval-Augmented Generation after completing the RAG module

## Author
  Charleen
