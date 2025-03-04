# OpenAI Product Pricer

## Overview
OpenAI Product Pricer is a project that leverages OpenAI's models to estimate product prices based on given descriptions. It includes functionality for fine-tuning OpenAI models using custom datasets and testing the pricing predictions.

## Features
- Fine-tunes OpenAI models with a dataset of product descriptions and prices.
- Predicts prices for new product descriptions.
- Includes scripts for training, validation, and testing.

## Repository Structure
```
openai-product-pricer/
│── items.py                     # Contains item-related functions or classes
│── openai_product_pricer.ipynb  # Jupyter notebook for fine-tuning and testing
│── testing.py                   # Script for testing the trained model
│── fine_tune_train.jsonl        # Training dataset for fine-tuning
│── fine_tune_validation.jsonl   # Validation dataset
│── .gitignore                   # Files to ignore in version control
│── __pycache__/                 # Compiled Python files (ignored)
```

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Sidi-boi/openai-product-pricer.git
   cd openai-product-pricer
   ```
2. Install required dependencies:
   ```sh
   pip install openai pandas numpy huggingface_hub openai jsonl dotenv pickle transformers matplotlib
   ```

## Usage
### Fine-tuning the Model
Prepare the training and validation data in JSONL format (`fine_tune_train.jsonl`, `fine_tune_validation.jsonl`), then execute the Jupyter notebook `openai_product_pricer.ipynb` to fine-tune the model.


## Contributing
Feel free to fork the repository and submit pull requests with improvements!


