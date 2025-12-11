# AML-finalProject
Final Project for Applied Machine Learning w/ Python

This project was done by Anvith Maddipoti, Jessica Nguyen, Caitlyn Pratt, and Lucy Schilling.

## Goals
The goal of this project was to create an LSTM model capable of differentiating between fake and real articles, helping reduce the spread of misinformation as AI-generated content continues to grow exponentially.

## Dataset
The link to the dataset used: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset/data

The link to the scrapped dataset: https://www.kaggle.com/datasets/mahdimashayekhi/fake-news-detection-dataset/data

### Description
The Kaggle dataset includes  two CSV files: `Fake.csv` and `True.csv`, with 23,502 and 21,417 rows respectively. The files contain articles publish between 2016 to 2018. Each file corresponds to a category: `Fake.csv` contains fake news articles, while `True.csv` contains real ones.

### Features
The  features in our dataset are
- title - title of the article
- text - text in the article
- subject - subject of the article
- date - date when the article was published

## Reproducibility
Our results can be replicated using Google Colab with any of following files:
1. The final version: `FakeNewsProject_FinalVer.ipynb` with  `projectver2_fake_news_lstm_model.keras`, `projectver2_label_encoder.pkl`, and `projectver2_tokenizer.pkl`
2. The model and pre-processing: `FakeNewsDetectionProject2.ipynb`
3. The scrapped version with RoBERTa: `FakeNewsDetectionProject.ipynb`

## Additional Notes
For more information on our results, please refer to our paper (`I320D Project: Report.pdf`) or presentation (`FakeNewsDetectionPresentation.pptx`).

## References
Alpert, H. (2022, March 5). How to use Beautiful Soup to parse text for NLP projects. Medium. https://halpert3.medium.com/how-to-use-beautiful-soup-to-parse-text-for-nlp-projects-48acc9145f89

Clmentbisaillon (2024, April 19) fake-and-real-news-dataset [Data set] Kaggle. https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset/data 

Devêci, B. (2025, May). Fake-News Detection with TF-IDF & BERT [Notebook]. Kaggle. https://www.kaggle.com/code/busradeveci/fake-news-detection-with-tf-idf-bert#Fake-News-Detection-Project:-Summary-and-Evaluation

Marcotcr. (2021). LIME: Explaining the predictions of any machine learning classifier [Code repository]. GitHub. https://github.com/marcotcr/lime

Mashayekhi, M. (2025, May). Fake News Detection Dataset [Data set]. Kaggle. https://www.kaggle.com/datasets/mahdimashayekhi/fake-news-detection-dataset

Rivaldo, R. (2020). Sentiment-Analysis [Code repository]. GitHub. https://github.com/RichardRivaldo/Sentiment-Analysis?tab=readme-ov-file

Sentdex. (2018, February 27). Sentiment Analysis in Python with TextBlob and VADER Sentiment (also Dash p.6) [Video]. YouTube. https://www.youtube.com/watch?v=qTyj2R-wcks
