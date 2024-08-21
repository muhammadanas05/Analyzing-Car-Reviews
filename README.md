# Analyzing Car Reviews with LLMs

### Car-ing is sharing,
an auto dealership company for car sales and rental, is leveraging 
### Large Language Models (LLMs) 
to enhance their services. As a newly recruited AI and NLP developer, you have been tasked with prototyping a chatbot app with various functionalities to assist both customers and human agents.

The solution involves using pre-trained Hugging Face LLMs to perform tasks such as sentiment analysis, translation, summarization, and question answering on textual prompts.

## Load the Dataset

The dataset `car_reviews.csv` is loaded into a pandas DataFrame. The first few rows of the dataset are displayed to understand its structure.

## Sentiment Analysis with Transformers

A sentiment analysis model is initialized and used to classify the sentiment of car reviews in the dataset. The sentiment labels are converted to binary integers (1 for POSITIVE, 0 for NEGATIVE), and the predictions are displayed.

## Calculate Accuracy and F1 Score

Accuracy and F1 score metrics are calculated to evaluate the performance of the sentiment analysis model. True labels and predicted labels are used to compute these metrics, and the results are displayed.

## Translation and BLEU Score Evaluation

The translation pipeline translates a segment of text from English to Spanish. The BLEU score is calculated to evaluate the quality of the translation by comparing it to reference translations.

## Extractive Question Answering with Transformers

An extractive question answering model is used to answer a specific question based on a given review. The model extracts the relevant information from the review, and the answer is displayed.

## Text Summarization

The summarization pipeline generates a summary of the last review in the dataset. The summarized text is displayed to provide a concise overview of the review content.
