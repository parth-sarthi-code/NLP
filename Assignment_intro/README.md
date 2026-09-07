# NLP Lab - Introduction Assignment

## Overview
This module introduces foundational data engineering for NLP, covering multimodal asset ingestion and full text preprocessing pipelines.

## Notebooks
- **[Task_1.ipynb](file:///home/parth/Lab/NLP/Assignment_intro/notebooks/Task_1.ipynb)**: Multimodal Data Ingestion & Inspection
  - Ingests and inspects plain text, compressed zipped CSV, semi-structured JSON, images, audio, video, and Excel workbooks.
- **[Task_2.ipynb](file:///home/parth/Lab/NLP/Assignment_intro/notebooks/Task_2.ipynb)**: NLP Preprocessing & Feature Extraction
  - Implements text normalization (slang/contractions/regex), tokenization, frequency analysis, Porter Stemmer vs WordNet Lemmatizer, spaCy NER, NLTK POS tagging, and TF-IDF vectorization.

## Data Directory
The `data/` directory contains sample datasets across media formats:
- `text/`: Literature corpus (`1342-0.txt`)
- `csv/`: Iris dataset archive (`iris.csv.zip`)
- `json/`: Restaurant records (`restaurant.json`)
- `images/`: Image asset (`convertico-ninja-girl-jpg.jpg`)
- `audio/`: Tone test signal (`tone-test.mp3`)
- `video/`: Video demo (`video.mp4`)
- `xlsx/`: Enterprise transaction workbook (`Online Retail.xlsx`)
