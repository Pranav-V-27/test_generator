# Text Generation using LSTM

## Overview
This project utilizes LSTM (Long Short-Term Memory) networks to generate text based on a provided dataset. The model is trained on a sample of text data and can be used to generate new sequences of text.

## Table of Contents
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Generating Text](#generating-text)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Disclaimer](#disclaimer)
- [License](#license)

## Dataset
The project uses the "got1.txt" file as the dataset. The raw text is preprocessed to remove unnecessary characters and create a cleaned dataset for training.

## Data Cleaning
The `clean_text` function is used to remove unwanted characters, punctuation, and whitespace from the raw text.

## Model Architecture
The LSTM model is defined using Keras with the following architecture:
- Embedding Layer
- Dropout Layer
- LSTM Layers
- Bidirectional LSTM Layer
- GlobalMaxPooling1D Layer
- Dense Layers

## Training
The model is trained using the cleaned and preprocessed dataset. Training details, such as accuracy and loss, can be visualized using the provided code.

## Generating Text
The trained model is capable of generating new text based on a provided seed text. The `predict_words` function takes a seed text and predicts the next words in the sequence.

## Usage
To use the code:
1. Install the necessary dependencies (`pip install keras`).
2. Run the provided code cells in the Jupyter notebook or script.
3. Use the trained model to generate text based on a seed.

## Dependencies
- Keras
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Seaborn
- NLTK

## Disclaimer
This project is for educational and experimental purposes. The generated text may not always make sense, and the model's output should not be taken as factual or accurate. The author is not responsible for any misuse or misinterpretation of the generated content.



Feel free to explore and modify the code for your own text generation experiments!
