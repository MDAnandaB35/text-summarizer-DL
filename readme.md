# Text Summarization with Deep Learning

This repository contains two Jupyter notebooks demonstrating different approaches to text summarization:

- [`NLP_text_summarizer.ipynb`](NLP_text_summarizer.ipynb): Implements a simple extractive text summarization method using NLTK.
- [`How_to_build_own_text_summarizer_using_deep_learning.ipynb`](How_to_build_own_text_summarizer_using_deep_learning.ipynb): Provides a comprehensive, step-by-step guide to building an abstractive text summarizer using deep learning (Keras, TensorFlow).

## Project Structure

- `NLP_text_summarizer.ipynb`: Extractive summarization using frequency-based scoring of sentences.
- `How_to_build_own_text_summarizer_using_deep_learning.ipynb`: Abstractive summarization using a sequence-to-sequence model with attention.
- `NLU Final Project Introduction.docx` / `NLU Final Project Introduction.pdf`: Project documentation.

## Requirements

- Python 3.6+
- Jupyter Notebook
- Libraries:
  - nltk
  - keras
  - tensorflow
  - pandas
  - numpy
  - matplotlib
  - scikit-learn
  - bs4 (BeautifulSoup)

Install dependencies with:

```sh
pip install nltk keras tensorflow pandas numpy matplotlib scikit-learn beautifulsoup4
```

## Usage

1. Download or clone this repository.
2. Open the notebooks in Jupyter Notebook or JupyterLab.
3. For the deep learning notebook, download the [Amazon Fine Food Reviews dataset](https://www.kaggle.com/snap/amazon-fine-food-reviews) and update the path in the notebook if necessary.
4. Run the cells sequentially to preprocess data, train models, and generate summaries.

## References

- [Comprehensive Guide to Text Summarization using Deep Learning in Python](https://www.analyticsvidhya.com/blog/2019/06/comprehensive-guide-text-summarization-using-deep-learning-python/)
- [Amazon Fine Food Reviews Dataset](https://www.kaggle.com/snap/amazon-fine-food-reviews)

## License

This project is for educational purposes only