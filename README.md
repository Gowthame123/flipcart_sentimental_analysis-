# Product Sentiment Analysis

## Overview

This project involves sentiment analysis on product reviews scraped from Flipkart. The goal is to analyze customer reviews for various products and determine their sentiment (Positive, Negative, or Neutral). The analysis is performed using multiple methods, including TextBlob and Vader Sentiment Analysis. The project also includes visualizations for a better understanding of the sentiment distribution and review insights.

## Dataset

The dataset consists of the following columns:
- **rating**: Rating given by the customer (1-5).
- **review_summary**: Summary of the customer review.
- **review_description**: Detailed description of the customer review.
- **product_name**: Name of the product being reviewed.
- **Price**: Price of the product.
- **product_id**: Unique identifier for each product.
- **compound**: Compound sentiment score from Vader Sentiment.
- **compound_sentiment**: Sentiment classification based on compound score.
- **rating_sentiment**: Sentiment based on rating (Positive, Negative, or Neutral).
- **Sentiment**: Sentiment from TextBlob (Positive, Negative, or Neutral).
- **Polarity**: Polarity score from TextBlob.
- **TextBlob_Sentiment**: Sentiment classification from TextBlob.

## Requirements

- pandas
- matplotlib
- seaborn
- textblob
- nltk
- wordcloud

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/product-sentiment-analysis.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure that you have the necessary NLTK datasets:
    ```python
    import nltk
    nltk.download('vader_lexicon')
    ```

4. Run the main script:
    ```bash
    python main.py
    ```

## Features

- **Sentiment Analysis**: Analyze sentiment using both TextBlob and Vader.
- **Data Visualization**: Generate various visualizations, including:
  - Sentiment distribution by product.
  - Wordcloud for positive and negative sentiments.
  - Rating vs sentiment analysis.
- **Data Processing**: Clean and preprocess the dataset to prepare it for analysis.

## Data Visualizations

The following visualizations are included in the project:

1. **Sentiment Distribution by Product**: A bar chart showing the sentiment distribution (positive, negative, neutral) for each product.
2. **Wordcloud**: A wordcloud to visualize the most frequently mentioned words in positive and negative reviews.
3. **Rating vs Sentiment**: A scatter plot comparing ratings with sentiment polarity.
4. **Sentiment Score Distribution**: A histogram of sentiment scores to understand the distribution of sentiments.

## How to Contribute

1. Fork the repository.
2. Create a new branch.
3. Implement your changes.
4. Test your changes.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- TextBlob: For performing sentiment analysis.
- Vader Sentiment: For compound sentiment score calculation.
- WordCloud: For generating word clouds from review texts.
- Matplotlib & Seaborn: For data visualizations.

   
