# Natural Language Processing (NLP) Lab Repository

Comprehensive laboratory coursework and practical implementations for Natural Language Processing (CSET346), covering multimodal data ingestion, text preprocessing pipelines, lexical normalization, language modeling, and semantic ontology exploration with WordNet.

---

## Repository Structure

```
NLP/
├── README.md
├── .gitignore
├── ASSIGNMENT- 1/
│   └── 2026_ODD_Week_1_Assignment_Intro.pdf
├── Assignment_intro/
│   ├── README.md
│   ├── data/
│   │   ├── audio/ (tone-test.mp3)
│   │   ├── csv/ (iris.csv.zip)
│   │   ├── images/ (convertico-ninja-girl-jpg.jpg)
│   │   ├── json/ (restaurant.json)
│   │   ├── text/ (1342-0.txt)
│   │   ├── video/ (video.mp4)
│   │   └── xlsx/ (Online Retail.xlsx)
│   └── notebooks/
│       ├── Task_1.ipynb   # Multimodal Data Ingestion & Inspection
│       └── Task_2.ipynb   # NLP Preprocessing & Feature Extraction Pipeline
├── Assignment_01/
│   ├── README.md
│   └── notebooks/
│       ├── Task_1.ipynb   # Brown Corpus Preprocessing & Lexical Statistics
│       ├── Task_2.ipynb   # Stemming vs. Lemmatization Comparison
│       ├── Task_3.ipynb   # Minimum Edit Distance Spell Correction
│       └── Task_4.ipynb   # N-gram Language Modeling (Unigrams/Bigrams/Trigrams)
└── Assignment_02/
    ├── README.md
    └── notebooks/
        ├── Task_1.ipynb   # WordNet Exploration & Polysemy Analysis
        ├── Task_2.ipynb   # Hypernym Hierarchy & Taxonomic Lineage
        ├── Task_3.ipynb   # WordNet Semantic Path Similarity
        └── Task_4.ipynb   # Homonym Sense Disambiguation & Context Clues
```

---

## Modules Overview

### 1. [Assignment Intro: Foundations & Multimodal Data](file:///home/parth/Lab/NLP/Assignment_intro/README.md)
- **Task 1**: Parsing and analyzing 7 distinct file formats (`.txt`, `.csv.zip`, `.json`, `.jpg`, `.mp3`, `.mp4`, `.xlsx`).
- **Task 2**: End-to-end NLP preprocessing pipeline (noise reduction, contraction expansion, tokenization, Porter Stemmer vs. WordNet Lemmatizer, spaCy NER, POS tagging, and TF-IDF matrix).

### 2. [Assignment 01: Corpora Processing & Language Models](file:///home/parth/Lab/NLP/Assignment_01/README.md)
- **Task 1**: Sentence segmentation and stopword removal on the NLTK Brown Corpus.
- **Task 2**: Comparative morphological evaluation of Stemming vs Lemmatization on target benchmarks (`playing`, `studies`, `running`, `better`, `cars`).
- **Task 3**: Levenshtein Minimum Edit Distance algorithm for spelling correction across isolated tokens and full sentences.
- **Task 4**: Unigram, Bigram, and Trigram frequency modeling on Brown Corpus.

### 3. [Assignment 02: Lexical Semantics & WordNet Ontologies](file:///home/parth/Lab/NLP/Assignment_02/README.md)
- **Task 1**: WordNet synsets querying, POS tagging, definition mapping, and polysemy case studies.
- **Task 2**: Taxonomic hypernym hierarchy traversal from leaf synsets to root node (`entity.n.01`) with depth metrics.
- **Task 3**: Semantic similarity metrics (`path_similarity`, `wup_similarity`, lowest common hypernyms) across concept pairs.
- **Task 4**: Word sense disambiguation (WSD) for homonyms (`bank`, `bat`, `bark`, `light`, `match`) using surrounding context clues.

---

## Installation & Environment Setup

```bash
# Clone the repository
git clone https://github.com/parth-sarthi-code/NLP.git
cd NLP

# Install required dependencies
pip install nltk spacy pandas numpy matplotlib seaborn openpyxl scikit-learn

# Download spaCy small English pipeline
python -m spacy download en_core_web_sm
```
