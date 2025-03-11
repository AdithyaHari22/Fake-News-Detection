<<<<<<< HEAD
# Fake-News-Classifier
A Fake News detection system using BERT and Data Augmentation on the Fakeddit dataset
=======
# Fake News Detection Using BERT and Data Augmentation

## Overview
This project develops a robust fake news detection system by fine-tuning a pre-trained BERT model and applying data augmentation via synonym replacement. The approach improves model generalization and achieves a test accuracy of **81.00%**. The project uses the Fakeddit dataset (preprocessed) and leverages libraries such as PyTorch, Hugging Face Transformers, and NLTK.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Contributions](#contributions)
- [Acknowledgments](#acknowledgments)

## Dataset
The project uses the **Fakeddit dataset** which has been preprocessed to remove null values and irrelevant columns. Detailed information about the dataset is available in [dataset_description.md](dataset_description.md).

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/<YourUsername>/Fake_News_Detection.git
   cd Fake_News_Detection

2. pip install -r requirements.txt

## Usage

1. Open the Fake_news_detection.ipynb notebook in VS Code or Jupyter Notebook
2. Follow the instructions in the notebook to preprocess the data, perform data augmentation, fine tune the BERT Model and evaluate the results.
3. The notebook is designed to be run on Google Colab for GPU support.


## Contributions

Adithya Hari - Implemented Data Augmentation, fine tuned the BERT Model and developed the evaluation pipeline.


## Acknowledgements

 - Thanks to the Hugging Face Transformers library for providing pre-trained BERT model
 - NLTK for enabling the synonym replacement data augmentation.
 - Thanks to the providers of the Fakeddit dataset Nakamura, Kai and Levy, Sharon and Wang, William Yang. [Fakeddit: A New Multimodal Benchmark Dataset for Fine-grained Fake News Detection](https://arxiv.org/abs/1911.03854).


>>>>>>> 717f0e2 (Initial commit with project structure and files)
