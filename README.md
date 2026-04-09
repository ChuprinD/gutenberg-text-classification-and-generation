# Deep Learning Minor - Assignment 3

This project implements text classification and generation using the
Project Gutenberg dataset.


## Project structure

The project consists of four notebooks:

-   `01_data_preparation.ipynb` - data loading, cleaning, and
    chunking
-   `02_classical_models.ipynb` - Conv1D and LSTM classification
-   `03_transformer_classification.ipynb` - BERT-based classification
-   `04_text_generation.ipynb` - conditional text generation and
    evaluation


## Dataset

Place the dataset in:

data/raw/

Required structure:

data/raw/Project Gutenberg/ (book text files)\
data/raw/pg_catalog.csv


## Setup

Create virtual environment:

python -m venv .venv

Activate (Windows):

.venv`\Scripts`{=tex}`\activate`{=tex}

Install dependencies:

pip install -r requirements.txt


## Run

Execute notebooks in order:

1.  01_data_preparation.ipynb\
2.  02_classical_models.ipynb\
3.  03_transformer_classification.ipynb\
4.  04_text_generation.ipynb

