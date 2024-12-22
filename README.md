# Transformer-Based LLM for Text Summarization

## Overview
This repository contains the implementation of a custom Transformer-based Large Language Model (LLM) designed from scratch to perform text summarization. The project involves building the model architecture, training it on a public dataset, and evaluating its performance using industry-standard metrics.

## Objective
Develop a custom Transformer-based architecture to generate extractive and abstractive text summaries without relying on pre-trained models. The focus is on implementing core Transformer components and optimizing the architecture for high-quality summarization results.

## Features
- **Custom Transformer Model:** Implementation of core components such as encoder, decoder, multi-head attention, and position-wise feed-forward networks.
- **Positional Encoding:** Ensures the model captures sequential relationships in text.
- **Summarization Techniques:** Supports both extractive and abstractive summarization.
- **Model Training:** Includes tokenization, padding, batching, and loss function optimization.
- **Performance Metrics:** Evaluates generated summaries using ROUGE scores and manual quality checks.

## Dataset
Utilizes a public text summarization dataset available on Kaggle: [Text Summarization Dataset](https://www.kaggle.com/code/lusfernandotorres/text-summarization-with-large-language-models/input)

## Getting Started
### Prerequisites
- Python 3.x
- TensorFlow or PyTorch
- Required libraries: `numpy`, `pandas`, `sklearn`, etc.

