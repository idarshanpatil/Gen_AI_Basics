# Gen AI Basic

A hands-on introduction to core NLP concepts using NLTK and scikit-learn — covering tokenization, stemming, lemmatization, POS tagging, named entity recognition, stopword removal, and text vectorization (CountVectorizer, TF-IDF), with notes on Word2Vec's CBOW and Skip-gram architectures.

## Contents

The notebook (`Gen_AI_Basic_1.ipynb`) covers:

- **Tokenization** — splitting text into words/sentences (`word_tokenize`, `sent_tokenize`)
- **Frequency Distribution** — counting word occurrences with `FreqDist`
- **Stemming** — reducing words to root forms with `PorterStemmer`
- **Lemmatization** — reducing words to dictionary base forms
- **POS Tagging** — assigning part-of-speech tags to words
- **Named Entity Recognition (NER)** — identifying entities like people, places, organizations
- **Stopword Removal** — filtering out common low-information words
- **Vectorization** — converting text to numeric vectors with `CountVectorizer`
- **TF-IDF** — weighting words by importance across documents
- **CBOW & Skip-gram** — word embedding concepts (Word2Vec)

## Setup

```bash
pip install -r requirements.txt
```

Then in Python, download the required NLTK resources:

```python
import nltk
nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('averaged_perceptron_tagger_eng')
nltk.download('maxent_ne_chunker_tab')
nltk.download('words')
nltk.download('stopwords')
nltk.download('wordnet')
```

## Usage

Open the notebook with Jupyter:

```bash
jupyter notebook Gen_AI_Basic_1.ipynb
```

## Requirements

- Python 3.11+
- nltk
- scikit-learn
- pandas

## License

This project is for personal learning purposes.
