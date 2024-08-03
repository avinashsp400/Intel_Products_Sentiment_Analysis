# Intel Product Sentiment Analysis

The Intel Products Sentiment Analysis project aims to analyze product reviews of Intel products using various machine learning and natural language processing techniques. We focus on sentiment analysis, clustering, keyword extraction, and making recommendations based on product categories. The dataset used in this project is obtained through web scraping from online retail platforms.

## Dataset

The primary dataset used in this project includes customer reviews of various Intel products. The dataset contains multiple fields such as review text, ratings, product categories, and additional attributes like 'Color'. The data is collected using web scraping techniques from online retail platforms such as Amazon and Flipkart.

## Project Structure

The project is organized into the following main components:

### Web Scraping

- Scraping reviews from online retail platforms.
- Cleaning and formatting the scraped data for analysis.

### Data Preprocessing

- Handling missing values and formatting data fields.
- Extracting specific attributes, such as 'Color:', from dictionary-formatted data in the 'style' column.

### Sentiment Analysis

- Using PyTorch to build and train sentiment analysis models.
- Implementing neural network architectures for predicting the sentiment of reviews.
- Evaluating the model's performance using appropriate metrics.

### Clustering

- Applying TF-IDF vectorization on the review texts.
- Using scikit-learn to perform clustering on the TF-IDF vectors.
- Analyzing the resulting clusters to identify patterns and common themes in the reviews.

### Keyword Extraction

- Extracting significant keywords from the reviews to identify common positive and negative aspects.
- Using extracted keywords for sentiment classification and clustering.

### Recommendation System

- Developing a recommendation system based on product categories.
- Providing product suggestions to users based on their review sentiments and preferences.

## Key Features

- **Web Scraping**: Collecting real-time data from online retail platforms.
- **Data Handling**: Efficient data preprocessing to ensure the quality of the dataset.
- **Sentiment Model**: Robust sentiment analysis using deep learning techniques.
- **Clustering Analysis**: Discovering hidden patterns in the reviews through clustering.
- **Keyword Extraction**: Identifying key aspects that drive customer opinions.
- **Product Recommendations**: Personalized product recommendations based on analyzed data.

## Tools and Libraries

- **Python**: The main programming language used for this project.
- **BeautifulSoup and Scrapy**: For web scraping and data collection.
- **PyTorch**: For building and training sentiment analysis models.
- **scikit-learn**: For clustering and other machine learning tasks.
- **Pandas and NumPy**: For data manipulation and analysis.
- **NLTK and SpaCy**: For natural language processing tasks.
- **Matplotlib and Seaborn**: For data visualization.
