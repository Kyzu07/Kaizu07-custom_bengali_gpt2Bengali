# GPT-2 Bengali Language Model

## Overview

This repository houses a custom GPT-2 Bengali Language Model, a project dedicated to fine-tuning the GPT-2 model on a Bengali literature dataset. The objective is to create a language model that can generate contextual texts while maintaining the distinctive writing styles of renowned Bengali writers such as Rabindranath Tagore, Kazi Nazrul Islam, Sukumar Roy, and more.

## Project Highlights

- **Dataset Creation:**
  - Curated and prepared a Bengali literature dataset for training.

- **Data Preprocessing:**
    In preparing the Bengali literature dataset for GPT-2 Bengali Language Model training, standard preprocessing techniques were applied:
  
  - **Unicode Normalization:**
    - Ensured uniformity by normalizing Unicode characters.
  
  - **Removing Special Characters:**
    - Eliminated non-alphanumeric characters, punctuation, and symbols.
  
  - **Stopword Removal:**
    - Removed common Bengali stopwords.

- **Tokenization:**
  - Utilized different tokenization methods to process the dataset.

- **Data Visualizations:**
  - Created visualizations to explore and understand the characteristics of the Bengali literature dataset.

- **Model Training:**
  - Fine-tuned the GPT-2 model for 10 hours on 2 T4 GPUs.

## Generated Texts

The trained model can generate contextual texts in the writing styles of renowned Bengali writers. Examples of generated texts are available in the [**Samples**](./samples) directory.

## Usage

To use the GPT-2 Bengali Language Model, follow the instructions in the [**Usage Guide**](./docs/usage.md).

## Results

Check out the [**Results**](./docs/results.md) to explore the performance of the model, including sample generated texts.

## Acknowledgments

This project wouldn't have been possible without the support of the Bengali literature community and the open-source contributions from the GPT-2 project.

Feel free to explore the code, experiment with the model, and contribute to its improvement!

