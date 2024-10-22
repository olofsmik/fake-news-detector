<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Fake news detector

Final project for the Building AI course

## Summary

 This project aim to detect and recognise fake news

## Background

False or misleading information has become a significant problem in modern internet culture, specifically in blogs, online publications, and social networking platforms. It occurs everyday and spreads like wildfire, and people share it without confirming it. Fake news is often used to influence public opinion, elections, or other political agendas or it is created to generate ad revenue by attracting clicks and views (clickbait). I believe it is hard these days to know what to trust and even sometimes hard to know if it is ok to click on a certain link.  

## How is it used?

Everybody that reading stuff online will be potential users. If you are uncertain whatever a news article is real or fake, just copy the url or the content and paste it into the fake news detector. The fake news detector will be a separet web app that will respond with either FAKE or REAL.

## Data sources and AI methods

Dataset that is used: ISOT Fake News Dataset, taken from real world sources:
[https://www.kaggle.com/datasets/csmalarkodi/isot-fake-news-dataset]

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
| Paragraph   | Subject        |
| Paragraph   | Date it was published        |

Machine Learning Models
 - Logistic Regression
 - Decision Tree Classifier
 - Gradient Boosting Classifier

Programming language to use: Python

Pseudocode:
* Read in both real news and fake news and remove unnecessary elements in the data to make it easier to work with.
* Convert text into numerical values using techniques like TF-IDF (Term Frequency-Inverse Document Frequency).
* Split your dataset into training and testing subsets.
* Train the Model by feeding the preprocessed data to the selected model and ensure the model learns to differentiate between real and fake news.
* Predict the score.

## Challenges
The detector may perform well on news articles that follow a similar structure and language but there will be limitations on less structured content (e.g., social media posts).

The dataset is primarily structured as a binary classification, where articles are either labeled as "real" or "fake." This simplifies the problem but fake news is a complex phenomenon that often involves shades of truth which is ignored with this solution.

## What next?
Check if it is possible to integrated the fake news detactor on other platform as well to be able to flag news or articles as FAKE or REAL.
Use Additional Datasets to incorporate more diverse datasets to cover different domains.
