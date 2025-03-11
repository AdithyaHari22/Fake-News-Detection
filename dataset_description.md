### 2. dataset_description.md

# Dataset Description: Fakeddit Dataset

Thanks to the authors of the Fakeddit dataset: Nakamura, Kai and Levy, Sharon and Wang, William Yang. Please use think link to access the paper[Fakeddit: A New Multimodal Benchmark Dataset for Fine-grained Fake News Detection](https://arxiv.org/abs/1911.03854)

## Overview
The Fakeddit dataset is used in this project to develop a fake news detection system. It contains preprocessed news articles labeled as fake or real. The data has been cleaned to remove null values and irrelevant columns to focus on the text content for classification.

## Dataset Details
- **Source:** Fakeddit dataset (publicly available for fake news detection tasks).
- **Content:** Text articles along with corresponding labels indicating fake or real news.
- **Preprocessing:** 
  - Null values and irrelevant columns have been removed.
  - The text column has been cleaned and prepared for tokenization.
- **Usage:** The dataset is used to fine-tune a BERT model, augmented with synonym replacement to enhance data diversity.

## Data Augmentation
- **Technique:** Synonym Replacement using NLTK's WordNet.
- **Augmentation Ratio:** Approximately 30% of the training data augmented with a replacement probability of 20%.
- **Purpose:** To improve the diversity of the dataset and boost the model's generalization capabilities.

## File Format and Structure
- **Format:** The dataset is provided in TSV/CSV format.
- **Columns:** Typically includes a text column (news content) and a label column (fake or real).

## Limitations
- Class imbalance may be present.
- Some inherent noise in textual data despite preprocessing.

## Additional Information
For more detailed experimental settings and preprocessing steps, please refer to the [project report](Fake News Detection Using BERT and Data Augmentation.pdf)


