# Space News Exploration

LING 227 Final Project - Danny Farid and Ellen Zhang

## Required Packages for Running "word2vec_kMeans" and "LDA_VADER"

This README file provides information on the necessary packages needed to run code from two files:

1. "word2vec_kMeans" - A file implementing the word2vec and k-Means algorithms for topic modeling.
2. "LDA_VADER" - A file implementing the Latent Dirichlet Allocation (LDA) topic modeling algorithm and VADER sentiment analysis.

### Common Packages

These packages are required for both "word2vec_kMeans" and "LDA_VADER":

- numpy
- pandas
- gensim
- nltk
- matplotlib
- scikit-learn

### Additional Packages for "word2vec_kMeans"

To run the "word2vec_kMeans" file, you also need to install the following packages:

- yellowbrick
- plotly

### Additional Packages for "LDA_VADER"

Additionally, you need to download the following NLTK data. You can do this in Python with:

```python
nltk.download('vader_lexicon')
nltk.download('stopwords')
nltk.download('punkt')
```

### Installation

You can install the required packages for both files in the command line using pip:

```bash
pip install numpy pandas gensim nltk scikit-learn yellowbrick matplotlib plotly
```

## Running the code

Both files can be run like normal Jupyter notebooks, i.e. each code cell can be run sequentially.
