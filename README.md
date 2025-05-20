# Emotion Classification with BiLSTM and GloVe Embeddings

This project implements an emotion classification model using a Bidirectional LSTM (BiLSTM) neural network with GloVe word embeddings. The model classifies text into emotion categories (e.g., happy, sad, angry) based on a dataset of labeled text samples. The project includes preprocessing, model training, evaluation, and interactive prediction for new text inputs.

## Table of Contents

- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to classify emotions in text using a deep learning model. Key features include:

- **GloVe 100d embeddings** for rich word representations.
- **Bidirectional LSTM** layers to capture contextual information.
- **Preprocessing** with stopword removal and padding.
- **Class weighting** to handle imbalanced data.
- **Early stopping** to prevent overfitting.
- Interactive prediction for user-provided text inputs.

The model is trained on a dataset of text samples labeled with emotions and achieves improved accuracy through optimized architecture and training strategies.

## Requirements

To run this project, you need the following dependencies:

- Python 3.8+
- `numpy`
- `pandas`
- `nltk`
- `scikit-learn`
- `keras`
- `matplotlib`
- `tensorflow` (backend for Keras)

Install the dependencies using:

```bash
pip install numpy pandas nltk scikit-learn keras matplotlib tensorflow
