# Text Mining Project
This project is a text mining analysis on clickbait titles, aiming to identify the causes and patterns that make a title a clickbait. The analysis is performed using Latent Semantic Analysis (LSA) and the R programming language.

## Dataset

The dataset used for this project contains 32,001 titles, each labeled as either clickbait or non-clickbait. The data is preprocessed by converting to lowercase, removing punctuation, and stopwords.

## Analysis

The analysis is divided into two main parts, each focusing on a specific word that seems to be correlated with clickbait titles: `favorite` and `laugh`.

### Analysis on the word `favorite`

The analysis starts by querying the term `favorite` and checking its correlation with clickbait titles. The process is then iterated by adding more related terms to the query, such as `based`, `zodiac`, and `sign`. The final query, `favorite based zodiac sign`, shows a strong correlation with clickbait titles, retrieving 76% of the clickbait titles in the top 16,000 results.
This suggests that one of the causes of clickbait titles is promising to discover personality features, favorite things, or other peculiarities based on the reader's zodiac sign.

### Analysis on the word `laugh`

The second part of the analysis focuses on the word `laugh`. The process is similar to the first part, with the final query being `laugh guaranteed make tweets`. This query retrieves 80% of the clickbait titles in the top 16,000 results.
The interpretation of this result is that another cause of clickbait titles is that they contain tweets or other things that are guaranteed to make the reader laugh.

## Conclusion
The project successfully identifies two significant causes of clickbait titles: promising to reveal personality traits based on the reader's zodiac sign, and offering content that is guaranteed to make the reader laugh. These findings provide insights into the patterns and strategies used by content creators to attract clicks and engage readers.

## Usage

To run the analysis, you need to have R installed with the required packages (lsa, tm, dplyr, plot3D) or using Google Colab. The dataset is included in the repository as data.csv.

## Credits

This project was created by Alberico Arcangelo as part of a Text Mining course.
