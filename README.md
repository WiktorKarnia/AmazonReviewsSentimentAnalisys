# AmazonReviewsSentimentAnalysis

This project focuses on performing sentiment analysis on Amazon product reviews. The goal is to classify reviews as positive or negative, providing insights into customer opinions and product feedback.

## Features

- **Data Collection**: Scrapes Amazon product reviews using the `AmazonReviewScraper.py` script.
- **Data Preprocessing**: Processes and cleans the scraped data to prepare it for analysis.
- **Sentiment Analysis**: Utilizes machine learning models to classify the sentiment of reviews.
- **Model Training**: Includes scripts for training models on the dataset.
- **Fine-Tuning**: Allows fine-tuning of pre-trained models for improved accuracy.
- **Results Evaluation**: Provides tools to evaluate and visualize the performance of the sentiment analysis models.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/WiktorKarnia/AmazonReviewsSentimentAnalisys.git
   cd AmazonReviewsSentimentAnalisys
   ```

2. **Create a Virtual Environment**:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Train the Sentiment Analysis Model**:

   Use the `ModelTraining.py` script to train the model on a dataset or scraped data. Remember to provide a path to the dataset inside of the ModelTraining.py file.

   ```bash
   python ModelTraining.py
   ```

2. **Fine-Tune the Model**:

   If needed, fine-tune the model using the `FineTune.py` script. Provide both name of the model you're fine tuning and a path to the additional dataset inside the FineTune.py

   ```bash
   python FineTune.py
   ```

3. **Analyze Sentiment**:

   Use the `main.py` script to scrape and analyze the sentiment of reviews for a specific product. Add a link to the product inside of main.py.

   ```bash
   python AmazonSentimentAnalyzer.py
   ```

4. **Check Data**:

   Use the `CheckData.py` script to validate the data.

   ```bash
   python CheckData.py
   ```

