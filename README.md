![2024-05-08 141434](https://github.com/Asanta4/NLP-Seinfeld-or-Friends/assets/136238984/450ae644-af5c-46a7-adfb-59b5d1630741)

# Friends vs Seinfeld Dialogue Classifier

## Project Overview
This project focuses on developing a Natural Language Processing (NLP) model to classify dialogues from the popular TV shows "Friends" and "Seinfeld". Using 70,405 lines of dialogue from script data, the model employs various NLP techniques to process and vectorize the text, aiming to accurately identify the source TV show based solely on dialogue content.

## Dataset
The dataset comprises dialogue lines extracted from:
- **Friends**: 10 seasons (1994-2004)
- **Seinfeld**: 9 seasons (1989-1998)

In total, the dataset includes 70,405 lines of dialogue which have been meticulously labeled according to their respective shows.

## Technologies Used
- Python 3
- Libraries: NumPy, Pandas, scikit-learn, NLTK
- Jupyter Notebook

## Model Development
The model development process involved several key steps:
1. **Data Preprocessing**: Tokenization, removal of stopwords, and normalization of text.
2. **Feature Engineering**: Conversion of text data into numerical vectors using techniques like TF-IDF.
3. **Model Training**: Implementation of machine learning algorithms such as Logistic Regression, Support Vector Machine, and Random Forest.
4. **Model Evaluation**: Using metrics like accuracy, precision, recall, and F1-score to evaluate the performance.

## Results
The model achieved a high level of accuracy (details in the Jupyter Notebook). Detailed performance metrics and a confusion matrix are available to assess the model's effectiveness in classifying dialogues.
