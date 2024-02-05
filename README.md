OVERVIEW
This project aims to develop a machine learning model for the detection of disaster-related tweets. 
The dataset, obtained from Kaggle, consists of 7613 rows and 4 columns, providing information about tweets, their content, and their associated labels.


METHODOLOGY
1.Data Preprocessing:
-Handling missing values in the 'keyword' column.
-Tokenization, removing stopwords, and stemming/lemmatization of text data.

2.Named Entity Recognition (NER):

-Using both NLTK and spaCy for extracting location entities.

3.Feature Engineering:

-Encoding categorical features (keywords, locations) using one-hot encoding.

4.BERT-based Representation:

-Leveraging BERT for obtaining embeddings from tweet text.

5.Modeling:

-Training various models including Logistic Regression, SVM, Random Forest, and LightGBM.
-Evaluating model performance using accuracy metrics.
