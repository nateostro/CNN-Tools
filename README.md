# CNN-Tools

This project contains CNN Tools for finding all article links for a search term, pulling and cleaning article text, then classifying articles by sentiment and by publish date.

Author: Nathan Ostrowski @nathanostrowski

Each folder in this repository contains a complete mathematica notebook and a corresponding stylized pdf document fully documenting the notebook and its function.

Each folder is part of a larger CNN-Tools project, and each notebook is meant to be used after another in the order:

AllLinksRetriever --> ArticlesRetriever --> ArticlesCleaner --> ArticlesSentimentClassifier

The final result of running all four scripts with a given search parameter will be a dictionary where each key is an article date and each value is a classified article, presented as an array of positive, negative, and neutral sentiment classification values for each sentence in a given article.
