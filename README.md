# Tweets-NameEntityRecognition-NLP

# Introduction

This repository focuses on extracting appropriate name entities using both NLTK and SpaCy Name Entity Recognition models and identifying the most frequently mentioned company in these tweets and news articles. 

Name Entity Recognition is a very useful method to extract relevant information from unstructured text and can be extremely useful for various business usecases.

# Data Preparation

- The code loads and preprocesses news articles and tweets, filtering and cleaning text data in English.

- Named Entity Recognition (NER) is performed on news titles, text, and tweets using both NLTK and spaCy libraries, without and with sentence segmentation.

- Top 20 organizations are extracted, and their frequencies are displayed, providing insights into the most mentioned entities.

- The code efficiently utilizes parallel processing for spaCy NER to enhance performance.

- The output includes a side-by-side comparison of the extracted organizations for news titles, text, and tweets, showcasing the diversity of the mentioned entities.

- NER results are displayed for both NLTK and spaCy, offering a comprehensive analysis of organizations across different text segments.

- The execution time for spaCy NER on a sample of news articles is measured to assess computational efficiency.

- The code showcases proficiency in utilizing popular NLP libraries for information extraction and analysis.

- Cleaning functions ensure data quality by removing unnecessary characters and formatting issues.

- The code provides a detailed exploration of named entities in news articles and tweets, enhancing understanding of the prominent organizations in the analyzed text data
