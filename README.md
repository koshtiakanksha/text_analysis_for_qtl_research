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
   git clone <repo_link>
   cd <repo_folder>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Ensure that the dataset files (`QTL_text.json` and `Trait dictionary.txt`) are in the project directory.

## How to Run
- Open and execute the Jupyter Notebook (`Extended_Documented_Untitled.ipynb`).
- The script will:
  1. Load and clean text data.
  2. Generate word clouds.
  3. Train a Word2Vec model.
  4. Extract and match phrases with the trait dictionary.
  5. Display results and insights.

## Results
- **Word Cloud Visualizations** (`wordcloud_freq.png`, `wordcloud_tfidf.png`)
- **Word2Vec Similar Word Outputs**
- **Matched Phrases vs. Trait Dictionary Analysis**
- **Comparison of Word-based vs. Phrase-based Insights**

## Contributions
Feel free to fork the repository, improve the code, and submit a pull request.

## License
This project is for academic and research purposes only.

