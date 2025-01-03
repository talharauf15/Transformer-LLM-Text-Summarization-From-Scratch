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
Utilizes a public text summarization dataset available on Kaggle: [Text Summarization Dataset](https://www.kaggle.com/datasets/nileshmalode1/samsum-dataset-text-summarization)

## Getting Started
### Prerequisites
- Python 3.x
- TensorFlow or PyTorch
- Required libraries: `numpy`, `pandas`, `sklearn`, etc.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/talharauf15/Transformer-LLM-Text-Summarization-From-Scratch.git
   cd Transformer-LLM-Text-Summarization
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Preprocess the dataset:
   - Tokenize and batch the input text.
   - Apply padding and positional encodings.

2. Train the model:
   ```bash
   python train.py
   ```

3. Evaluate the model:
   ```bash
   python evaluate.py
   ```

4. Generate summaries:
   ```bash
   python generate_summary.py --input "Your input text here"
   ```

## Evaluation Metrics
- **Loss (Training & Validation):** Tracks model convergence.
- **ROUGE Scores:** Measures the overlap between generated and reference summaries.
- **Manual Evaluation:** Assesses relevance, coherence, and conciseness of summaries.

## Sample Results
- **Input Text:** Sample input from the dataset.
- **Generated Summary:** Output from the custom Transformer model.
- **Comparison:** ROUGE scores and qualitative analysis.

## Challenges and Insights
- Discussion of challenges faced during model design, training, and optimization.
- Insights into potential areas for improvement.

## Contribution
Contributions are welcome! Please fork the repository and submit a pull request with improvements or fixes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
