# Chinese Text Classifier

A binary classifier that can take a news article of unknown source written in Chinese and classify its origin as either Taiwanese (1) or Mainland Chinese (0). This can serve as an important tool to prevent the spread of misinformation in the Taiwan-China discursive battlespace. [test](https://colab.research.google.com/drive/1oDVAbhexTHU9SEOaqJZJ1tCOdbmBMFbB?usp=sharing)

## Notebook Architecture

This notebook is broken up into five sections: General Imports, Data Scraping, Data Preprocessing, Model, and Prediction. You can use this notebook to create an entire model from scratch, even without a preexisting dataset.

## Model Architecture

This model is an RNN that utilizes Google's BERT model trained for Chinese ('bert-base-chinese') as an embedding layer.
