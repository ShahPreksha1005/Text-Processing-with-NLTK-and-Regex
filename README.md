# Text Processing with NLTK and Regular Expressions

This repository contains lab work on natural language processing basics, focused on text processing, tokenization, frequency analysis, and regular expression applications. Through NLTK and custom regex patterns, this project explores core NLP tasks with step-by-step solutions.

## Project Overview

The project includes:
- **NLTK Installation and Setup**: Initial steps to set up the NLTK library and download required corpora.
- **Text Processing**: Basic text processing on a sample paragraph, including:
  - Tokenization and lowercase conversion
  - Stopword removal and filtering of non-alphanumeric tokens
  - Word frequency analysis with unique word counts
  - Identification of the most and least frequent words and the longest word
- **Regular Expressions**: Exercises covering:
  - Pattern matching for specific text features (e.g., alphabetic strings, words ending with 'b')
  - Extraction of repeated words, number-to-word patterns, and custom patterns involving specific words
- **Text Normalization**: Exploratory data analysis and visualization using NLTK and matplotlib to analyze word distributions and frequencies.

## Content and Key Files

- **Lab 0**: Setup of NLTK and necessary corpora.
- **Lab 1**: Implementing text processing functions and regular expression-based analysis.
  - Exercises include both foundational NLP tasks and specific regex-based patterns.

## Usage

To run this project, you need Python 3.x and the following libraries:
- `nltk`
- `re`
- `matplotlib`

### Installation of NLTK
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

### Sample Execution
```python
# Sample code to tokenize and filter words
from nltk.tokenize import word_tokenize
from nltk.corpus import stopwords

# Define your text and process with NLTK functions as demonstrated in each lab step.
```

## Key Takeaways
This project introduces basic text processing and regex techniques, offering a foundational understanding of NLP tasks like tokenization, word frequency analysis, and regular expressions for text pattern matching.

---
