# Sentiment Analysis Web Application

## Introduction
This is a Flask-based web application that analyzes the sentiment of user-provided text. The app uses **TextBlob** for sentiment analysis and displays detailed insights such as:
- Sentiment polarity (how positive or negative the text is).
- Subjectivity (how subjective or objective the text is).
- Tokenization and lemmatization of nouns.

Additionally, it provides a randomized pluralized version of the nouns from the input text for a creative touch.

---

## Features
- **Sentiment Analysis**: Calculates the polarity and subjectivity of the text.
- **Tokenization**: Splits the text into individual words and counts the tokens.
- **Noun Extraction**: Extracts nouns from the text and performs lemmatization.
- **Randomized Output**: Creates a randomized list of pluralized nouns.
- **Real-Time Performance**: Displays the time taken for processing.

---

## Prerequisites
Make sure you have the following installed on your system:
- Python 3.8+
- pip (Python package manager)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Khushi0389/SentimentAnalysis.git
   cd SentimentAnalysis
2. Install required dependencies:
     bash
      pip install -r requirements.txt
       Download necessary NLTK corpora: The script will automatically download required NLTK corpora such as punkt, averaged_perceptron_tagger, wordnet, and stopwords.

3. Usage
   Run the Flask application:
      bash
        python app.py
        Open your browser and navigate to:
4. Dependencies
    Flask
    Flask-Bootstrap
    TextBlob
   NLTK
5 Install all dependencies using:
   bash
   pip install -r requirements.txt
6. How It Works
   User enters text into the input box on the home page.
    The app processes the input using TextBlob to:
    Calculate polarity and subjectivity.
    Tokenize the text and extract nouns.
    Randomize and pluralize the nouns.
   The results are displayed in real-time along with the processing time.
Example Output
Input:
The quick brown fox jumps over the lazy dog.

Output:

Polarity: 0.0
Subjectivity: 0.0
Number of Tokens: 9
Extracted Nouns: fox, dog
Randomized Pluralized Nouns: foxes, dogs
Processing Time: 0.005 seconds
Future Improvements
Add support for multiple languages.
Enhance visualization with charts and graphs.
Integrate with external APIs for more advanced analytics.
