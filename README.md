# Dual Selective Attention Model for Sentiment and Emotion Identification with Explainable Cause Generation(SentEM_GEN)

This repository implements a model for sentiment and emotion classification using FinBERT embeddings, Bi-Directional LSTM, and a Selective Attention mechanism, designed for financial text analysis.

## Model Architecture

- **Feature Extraction**: Utilizes FinBERT/T5 to generate 768-dimensional embeddings.
- **Vector Enhancement**: Bi-Directional LSTM with 128 units per direction.
- **Selective Attention Network (SAN)**: Additive attention mechanism to focus on relevant text.
- **Classification**: Softmax layer for sentiment/emotion prediction using focal loss.

## Requirements

- Python 3.x, PyTorch, Transformers, NumPy, and other dependencies.

## Installation

1. Clone the repo:  
   `git clone https://github.com/ankan8145/SentEM_GEN.git`

## Citation

If used in research, please cite this work.

# main_arct.jpg

![Main Architecture Diagram](diagrams/main_arct.jpg)

## Overview

This repository contains an image illustrating the architecture for the project. The image, `main_arct.jpg`, can be found in the `diagrams/` directory. It serves as a visual aid to help understand the design and structure of the project components.

