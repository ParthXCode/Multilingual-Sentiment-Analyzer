# Multilingual-Sentiment-Analyzer
Multilingual Sentiment Analysis using XLM-RoBERTa-
This repository presents a Multilingual Sentiment Analysis system built using the XLM-RoBERTa transformer model from the Hugging Face ecosystem. The model is fine-tuned on an Amazon reviews dataset to classify text into sentiment categories across multiple languages.

The project demonstrates an end-to-end Natural Language Processing (NLP) pipeline, including data preprocessing, model training, evaluation, and deployment using an interactive interface.
Objectives-
To build a robust sentiment analysis model capable of handling multiple languages
To leverage transformer-based architectures for improved contextual understanding
To deploy the trained model for real-time inference
Features-
Multilingual sentiment classification
Transformer-based architecture (XLM-RoBERTa)
Efficient training using Hugging Face Trainer API
Scalable and modular pipeline
Interactive inference using Gradio
Model persistence for reuse and deployment
Dataset-

The model is trained on the Amazon Multilingual Reviews Dataset, which includes:

Review text
Language information
Sentiment labels
Technology Stack-
Programming Language: Python
Libraries & Frameworks:
Hugging Face Transformers
PyTorch
Datasets
Gradio
Platform: Google Colab
Methodology-
1. Data Preprocessing
Data loading and inspection
Text tokenization using XLMRobertaTokenizerFast
Label encoding and normalization
2. Dataset Optimization
Sampling a subset of the dataset to ensure efficient training
Shuffling and splitting into training and evaluation sets
3. Model Training
Model: XLMRobertaForSequenceClassification
Training managed using Hugging Face Trainer API
Hyperparameter configuration for optimal performance
4. Evaluation
Performance evaluated on a validation/test dataset
Metrics generated using built-in evaluation methods
5. Model Saving
Trained model stored for future inference and deployment
6. Deployment
Interactive web interface implemented using Gradio
