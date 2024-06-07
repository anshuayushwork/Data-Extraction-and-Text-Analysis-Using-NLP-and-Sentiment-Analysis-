# Data-Extraction-and-Text-Analysis-Using-NLP-and-Sentiment-Analysis-
Sentiment Analysis and Readability Metrics for Web Content

This project provides a comprehensive toolkit for analyzing the sentiment and readability of web content. The primary functionality includes fetching text from a given URL and calculating various sentiment scores, readability indices, and text complexity metrics. The analysis includes:

*Positive and Negative Score Calculation: Based on pre-defined word lists, the script identifies and counts positive and negative words in the text.
*Polarity and Subjectivity Scores: Metrics to understand the overall sentiment and subjectivity of the text.
*Readability Metrics: Including average sentence length, percentage of complex words, and the Fog Index.
*Word Count: Total number of words in the text.
The results are processed for multiple URLs and stored in an Excel file for further analysis. This project leverages libraries such as NLTK for natural language processing and BeautifulSoup for web scraping.

*Features
Fetch and process text content from URLs.
Calculate sentiment scores and readability metrics.
Output results in a structured Excel format.
*Technologies Used
1.Python
2.NLTK
3.BeautifulSoup
4.Pandas
5.Requests
*Usage
1.Place your input data (URLs) in an Excel file named Input.xlsx.
2.Ensure you have the necessary word lists (positive-words.xlsx, negative-words.xlsx, and StopWords_GenericLong.txt).
3.Run the script to process the URLs and generate the output file output.xlsx.
This project is ideal for those interested in sentiment analysis, natural language processing, and readability studies.
