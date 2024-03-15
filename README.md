# Sentiment-Analysis of Youtube Comment
### This project focuses on sentiment analysis of YouTube comments using the YouTube API for data extraction. It involves preprocessing and engineering features, followed by implementing an LSTM model using TensorFlow in a Jupyter Notebook environment. NLTK (Natural Language Toolkit) was utilized for natural language processing tasks. The goal was to create a robust model capable of accurately predicting sentiment in YouTube comments.

## Project Structure
The project is organized into several main components:

## Data Extraction:
Utilized the YouTube API to extract comments from YouTube videos.
Retrieved relevant metadata such as video ID, comment text.

## Data Preprocessing:
Cleaned and processed the raw comment data.
Conducted text normalization, including lowercasing, removing special characters, and tokenization.
Performed feature engineering to extract useful features from the comments.

## Model Implementation:
Implemented an LSTM (Long Short-Term Memory) model using TensorFlow for sentiment analysis.
Split the data into training and testing sets for model evaluation.
Trained the LSTM model on the training data and evaluated its performance on the testing data.

## Natural Language Processing (NLP):
Utilized NLTK for various NLP tasks such as tokenization, stopwords removal, and stemming/lemmatization.
Conducted sentiment analysis using NLTK's sentiment analysis tools to compare results with the LSTM model.

## Evaluation and Results:
Evaluated the LSTM model's performance using metrics such as accuracy, precision, recall, and F1 score.
Analyzed the results to assess the model's ability to predict sentiment in YouTube comments accurately.

## Requirements
- Python 3.x
- Jupyter Notebook
- TensorFlow
- NLTK
- YouTube Data API (obtain API key from Google Developer Console)

## Usage
- Clone the repository to your local machine.
- Install the required dependencies using pip install -r requirements.txt.
- Run the Jupyter Notebook files in sequential order to execute the data extraction, preprocessing, model implementation, and evaluation steps.
- Analyze the results and model performance metrics obtained from the notebook.
  
## Contributors
Prajina Pradhan

Shalini Gupta
