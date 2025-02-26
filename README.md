# Project 1: Text Analysis for QTL Research Papers

## Overview
This project analyzes text from QTL-related research papers to extract important terms, visualize patterns, and train models for word relationships. It involves data preprocessing, word cloud generation, Word2Vec modeling, and trait dictionary matching.

## Features
- **Preprocesses text** by tokenizing, lowercasing, and removing stopwords.
- **Generates word clouds** to visualize frequent and significant terms.
- **Trains a Word2Vec model** to identify relationships between words.
- **Extracts phrases** and compares them with a predefined trait dictionary.
- **Performs fuzzy matching** to improve the accuracy of trait dictionary comparisons.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/koshtiakanksha/text_analysis_for_qtl_research.git
   cd text_analysis_for_qtl_research
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run Jupyter Notebook
   ```bash
   jupyter notebook Project_1_akoshti.ipynb
   ```
3. Ensure that the dataset files (`QTL_text.json` and `Trait dictionary.txt`) are in the project directory.

## How to Run
- Open and execute the Jupyter Notebook (`Project_1_akoshti.ipynb`).
- The script will:
  1. Load and clean text data.
  2. Generate word clouds.
  3. Train a Word2Vec model.
  4. Extract and match phrases with the trait dictionary.
  5. Display results and insights.

## Results Summary
- **TF-IDF-based word clouds** highlighted more meaningful terms compared to frequency-based ones.
- **Word2Vec analysis** showed relevant word relationships but had minor noise due to limited data.
- **Phrase extraction improved insights**, capturing meaningful expressions like "gene mutation" instead of isolated words.
- **Trait dictionary matching required fuzzy matching**, as exact matches were low.
- **Further improvements** include lemmatization, better dictionary expansion, and more robust Word2Vec training.

## Contributions
Feel free to fork the repository, improve the code, and submit a pull request.

## License
This project is for academic and research purposes only.

