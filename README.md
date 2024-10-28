# Sentiment Analysis Web App

A web-based sentiment analysis application using Flask and Hugging Face's Transformers library. Users can input text, and the app will analyze and classify the sentiment as positive or negative, along with a confidence score. The application utilizes a pre-trained BERT model for robust sentiment analysis.

## Features

- **Frontend**: Created using HTML/CSS and JavaScript for capturing user input and displaying results.
- **Backend**: Flask-based API that processes text input and returns sentiment analysis results.
- **Model**: Uses Hugging Face's `distilbert-base-uncased-finetuned-sst-2-english` model, optimized for sentiment classification.

## Installation and Setup

1. **Clone the Repository**:
   git clone https://github.com/your-username/sentiment-analysis-webapp.git
   cd sentiment-analysis-webapp
   
2. **Install Required Dependencies: Ensure you have Python and pip installed, then run**:
  pip install -r requirements.txt
 
3. **Run the Application: Start the Flask application by running**:
  python app.py

4. **Access the Web App: Open your web browser and navigate to http://127.0.0.1:5000 to use the app**.

5. **Model Details**
  The application leverages the distilbert-base-uncased-finetuned-sst-2-english model from Hugging Face, a distilled version of BERT fine-tuned for sentiment analysis, ensuring efficient yet accurate results.

6. **Usage**:
  Open the app in your browser.
  Enter a piece of text you'd like to analyze.
  Click "Analyze" to receive sentiment feedback (positive or negative) with a confidence score.

7. **Project Structure**:
   
    app.py: Contains the Flask backend logic.
  
    templates/: HTML templates for the frontend.
    
    static/: Static files like CSS and JavaScript.
    
    requirements.txt: Lists the Python packages needed to run the app.
