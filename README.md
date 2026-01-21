# Sentiment-Analysis

This project focuses on scraping Yelp reviews, performing sentiment analysis using the **BERT** model, and visualizing sentiment distribution across the reviews. The reviews are scraped from Yelp using **BeautifulSoup**, while the sentiment analysis is powered by **Hugging Face's transformers library**. The project also includes visualizations to illustrate the sentiment distribution.

## Features

- Scrapes reviews from multiple pages of a Yelp business using **BeautifulSoup**.
- Analyzes sentiment using the **BERT** model (`nlptown/bert-base-multilingual-uncased-sentiment`).
- Visualizes sentiment distribution with **Matplotlib** and **Seaborn**.

## Tools Used

- **PyTorch**
- **Hugging Face transformers**: Pre-trained models for sentiment analysis.
- **Requests**: To send HTTP requests and scrape reviews.
- **BeautifulSoup4**: HTML parsing and web scraping.
- **Pandas**: Data manipulation for handling reviews.
- **Numpy**: Numerical computing.
- **Matplotlib**: Data visualization.
- **Seaborn**: Statistical visualization, built on Matplotlib.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SarangaVP/Sentiment-Analysis.git
   
2. Navigate to the project directory:
   
```bash
   cd Sentiment-Analysis
