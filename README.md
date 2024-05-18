#### Overview

This script demonstrates basic Natural Language Processing (NLP) techniques using the `nltk` library in Python. It includes text tokenization, stemming, lemmatization, and vectorization using both `CountVectorizer` and `TfidfVectorizer` from `sklearn`.

#### Prerequisites

- Install the necessary libraries using:
  ```bash
  pip install nltk sklearn
  ```

#### Steps in the Code

1. **Importing Libraries and Downloading NLTK Data**:
   - Import the `nltk` library and download the `punkt` tokenizer model.
   - Import additional necessary libraries from `nltk` and `sklearn`.

2. **Initial Setup**:
   - Define a paragraph of text for processing.

3. **Sentence Tokenization**:
   - Use `nltk.sent_tokenize` to split the paragraph into individual sentences.

4. **Word Tokenization**:
   - Use `nltk.word_tokenize` to split the paragraph into individual words.

5. **Stemming**:
   - Use the `PorterStemmer` from `nltk` to perform stemming on the words in each sentence, removing stopwords.

6. **Lemmatization**:
   - Use the `WordNetLemmatizer` from `nltk` to perform lemmatization on the words in each sentence, removing stopwords.

7. **Cleaning and Vectorization**:
   - Clean the sentences by removing non-alphabetic characters, converting to lowercase, and removing stopwords.
   - Stem the cleaned words and create a list of sentences (`corpus`).
   - Vectorize the corpus using `CountVectorizer` and `TfidfVectorizer` from `sklearn`.

This script demonstrates essential NLP preprocessing steps and provides a foundation for further text analysis and machine learning tasks.
