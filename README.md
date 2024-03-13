# Animated Movies Dataset Sentiment Analyzer

This project is a comprehensive analysis of an Animated Movies Dataset, focusing on sentiment analysis and exploratory data analysis (EDA) techniques. The goal is to gain insights into the sentiment and characteristics of animated TV series based on various features such as ratings, genres, and popularity.

## Project Overview

The project utilizes a dataset containing information about animated TV series, including their titles, episodes, release years, channels, production companies, techniques (traditional or CGI), IMDb ratings, and Google user ratings. The analysis involves data cleaning, preprocessing, and visualization to uncover patterns and trends within the dataset.

## Data Preprocessing

The project starts by importing the necessary libraries and loading the dataset. Data cleaning tasks are performed, including:

- Removing duplicate rows
- Converting data types
- Handling missing values
- Removing outliers

## Exploratory Data Analysis (EDA)

The EDA phase involves various techniques to gain insights into the dataset:

1. **Univariate Analysis**: This section explores individual features through histograms, bar plots, box plots, and value counts. It helps identify distributions, central tendencies, and potential outliers.

2. **Bivariate Analysis**: This phase examines the relationship between two features, such as IMDb ratings and Google user ratings. Scatter plots and correlation analysis are employed to visualize and quantify the relationships.

3. **Multivariate Analysis**: In this section, multiple features are analyzed simultaneously. Techniques like clustering (K-Means) and dimensionality reduction are utilized to identify patterns and group similar TV series based on their characteristics.

4. **Word Cloud and Text Analysis**: The project includes word cloud visualizations and text analysis techniques to explore the titles of the animated TV series, identifying frequently occurring words and themes.

## Sentiment Analysis

The project incorporates sentiment analysis techniques using the VADER (Valence Aware Dictionary and sEntiment Reasoner) library. This analysis aims to determine the sentiment polarity (positive, negative, or neutral) of the animated TV series based on their titles or descriptions.

## Results and Findings

The project presents insightful findings and visualizations based on the analysis, including:

- Distributions of ratings, episodes, and other features
- Correlations between ratings and popularity metrics
- Clustering of TV series based on their characteristics
- Word clouds highlighting common themes and words in titles
- Sentiment analysis results for individual TV series or the entire dataset

## Usage

To run this project locally, follow these steps:

1. Clone the repository or download the project files.
2. Install the required libraries (e.g., pandas, numpy, matplotlib, seaborn, wordcloud, nltk).
3. Run the Jupyter Notebook or Python script containing the code.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
