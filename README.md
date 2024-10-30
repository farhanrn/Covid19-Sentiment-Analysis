
# COVID-19 Sentiment Analysis in Indonesian Text

This project focuses on sentiment analysis of COVID-19-related text in Indonesian using natural language processing (NLP) techniques. The notebook includes a series of steps from data acquisition and preprocessing to feature engineering, and provides placeholders for machine learning modeling, evaluation, and deployment. 

## Project Overview

- **Language**: Indonesian
- **Sentiment Labels**: Positive, Negative
- **Tech Stack**: Python, Pandas, NLTK, Scikit-learn, Sastrawi, WordCloud

## Steps

### 1. Data Acquisition
The data is loaded and labeled with sentiment classes:
  - **Positive**: Positive sentiment
  - **Negative**: Negative sentiment

### 2. Text Preprocessing
A series of NLP preprocessing steps to clean and standardize text data:
  - **Case Folding**: Converts all text to lowercase.
  - **Slang Word Normalization**: Normalizes colloquial expressions using a predefined mapping.
  - **Stopword Removal**: Eliminates common Indonesian stopwords using NLTK.
  - **Stemming**: Reduces words to their base form with Sastrawi stemmer.

### 3. Feature Engineering
Transforms text data into numerical formats suitable for machine learning:
  - **Bag of Words (BoW) and N-Gram**: Converts text to vectors based on word frequency.
  - **TF-IDF**: Weights terms based on importance in the document and corpus.
  - **Feature Selection**: Applies chi-squared selection to identify top features.

### 4. Modeling (Machine Learning)
  Placeholder for implementing machine learning models on preprocessed data.

### 5. Model Evaluation
  Placeholder for evaluating the performance of the model.

### 6. Deployment
  Placeholder for deployment considerations.

### 7. Visualization (WordCloud)
  Uses WordCloud to visualize the frequency of words associated with different sentiment categories.

## Usage

1. **Install Dependencies**:
   Make sure you have the necessary Python libraries:
   ```bash
   pip install pandas numpy matplotlib sastrawi nltk scikit-learn wordcloud
   ```

2. **Run the Notebook**:
   Execute each cell in the notebook to preprocess the data, engineer features, and visualize word clouds.

## Future Work
- **Model Training and Evaluation**: Implement and compare various machine learning models.
- **Deployment**: Deploy the model as a simple API or web service for live sentiment analysis.

## Acknowledgments
- **Dataset**: The dataset used for this project focuses on COVID-19 sentiment in Indonesian text.
- **Libraries**: Thanks to Sastrawi for Indonesian NLP support and Scikit-learn for feature engineering.
