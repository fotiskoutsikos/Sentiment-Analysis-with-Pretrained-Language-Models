# Sentiment-Analysis-with-Pretrained-Language-Models

This notebook demonstrates the fine-tuning of a pretrained Transformer model on the Yelp Polarity dataset. It was developed as part of an assignment on natural language processing and model adaptation using the Hugging Face ecosystem.

## Project Overview

The main objective was to apply transfer learning techniques to perform binary sentiment classification on user-generated content. The notebook leverages Hugging Face's pipelines and dataset APIs for efficient experimentation.

## Dataset

- Yelp Polarity (via 🤗 `datasets`)
- Contains short user reviews labeled as either positive or negative

## Key Concepts

- Text tokenization and preprocessing
- Model fine-tuning with `Trainer` API
- Evaluation and performance metrics

## Dependencies

- Hugging Face Transformers
- Datasets, Torch, NumPy
