# Neural-Network-HW4

Name: Yeshwnath Narige   
ID : 700764035  

# Q1 : NLP Preprocessing Pipeline
This project demonstrates a basic Natural Language Processing (NLP) pipeline that processes input text through the following steps:

🔧 Features
Tokenization – Splits the sentence into individual words and punctuation.

Stopword Removal – Removes common English stopwords to retain only meaningful words.

Stemming – Applies Porter Stemming to reduce words to their root/base form.  

# Q2: Named Entity Recognition (NER) with spaCy
This project demonstrates the use of the spaCy library for Named Entity Recognition (NER) to extract meaningful entities from a sentence. The entities identified include persons, organizations, locations, dates, and other entities like works of art and numerical values.

🔧 Features
Named Entity Recognition (NER) using spaCy.

Extracts named entities such as people, organizations, dates, and locations.

Displays the entity text, label (type of entity), and the start and end character positions.


# Q3 : # Scaled Dot-Product Attention

This project demonstrates the **Scaled Dot-Product Attention** mechanism, which is a core concept in attention mechanisms used in models like Transformers. The attention mechanism computes a weighted sum of values (V) based on the similarity between queries (Q) and keys (K), which is scaled by the dimension of the keys to avoid large dot products.

### 🔧 Features

- Computes the scaled dot-product attention mechanism.
- Uses **Q** (Query), **K** (Key), and **V** (Value) matrices to calculate the attention weights and the final output.
- Applies softmax to the scaled attention scores for normalization.

# Q4 : Sentiment Analysis using HuggingFace Transformers
This project demonstrates how to perform Sentiment Analysis using the HuggingFace Transformers library. It utilizes a pre-trained sentiment analysis model from HuggingFace to analyze the sentiment of a given sentence and output both the label (positive/negative) and the confidence score.

🔧 Features
Uses the HuggingFace Transformers library to load a pre-trained sentiment analysis model.

Analyzes input sentences and classifies them as POSITIVE or NEGATIVE.

Outputs the sentiment label along with the confidence score.

