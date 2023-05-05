# Plagiarism-Detection

#Plagiarism Detection Project
This project aims to detect any possible plagiarism in documents using Natural Language Processing (NLP) techniques and the BERT model. The BERT model is a state-of-the-art deep learning model that has shown promising results in various NLP tasks, including plagiarism detection.

#Requirements
Python 3.x
PyTorch
Transformers library
Pandas library
Scikit-learn library

#Installation
Clone the repository to your local machine.
Install the required libraries using pip install -r requirements.txt.
Run the plagiarism_detection.py script to train and test the model.

#How it Works
The input documents are preprocessed using NLP techniques such as tokenization, stop word removal, and stemming.
The preprocessed documents are then fed into the BERT model, which extracts features from the text.
The features are then used to classify the documents as plagiarised or non-plagiarised based on a benchmark score.
The benchmark score can be adjusted to suit different use cases and requirements.
