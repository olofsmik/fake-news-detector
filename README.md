<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Fake news detector

Final project for the Building AI course

## Summary

 This project aim to detect and recognise fake news

## Background

False or misleading information that is reported as news are called fake news and has become a significant problem in modern internet culture, specifically in blogs, online publications, and social networking platforms. It occurs everyday and spreads like wildfire, and people share it without confirming it. Fake news is often used to influence public opinion, elections, or other political agendas. Or it is created to generate ad revenue by attracting clicks and views (clickbait). I believe it is hard these days to know what to trust and even sometimes hard to know if it is ok to click on a certain link.  

This is how you make a list, if you need one:
* Logistic Regression
* Decision Tree Classifier
* Machine learning (NLP)


## How is it used?
You copy the url to the content and paste it into the fake news detector which is a separate tool that response with FAKE OR REAL.
This could be used by all users

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods

Dataset that is used: ISOT Fake News Dataset, taken from real world sources:
[https://www.kaggle.com/datasets/csmalarkodi/isot-fake-news-dataset]

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
| Paragraph   | Subject        |
| Paragraph   | Date it was published        |

* Read in both real news and fake news and remove unnecessary elements in the data to make it easier to work with.
* Convert text into numerical features using techniques like TF-IDF (Term Frequency-Inverse Document Frequency)
* Train-Test Split: Split your dataset into training and testing subsets.
* Train the Model: Feed the preprocessed data to the selected model. Ensure the model learns to differentiate between real and fake news based on the textual features.
* Predict the store

AI methods:
Machine Learning Models - Logistic Regression
Deep Learning Models - LSTM (Long Short-Term Memory)

## Challenges
The detector may perform well on news articles that follow a similar structure and language but there will be limitation on less structured content (e.g., social media posts).

The dataset is primarily structured as a binary classification, where articles are either labeled as "real" or "fake." This simplifies the problem but fake news is a complex phenomenon that often involves shades of truth which is ignored with this solution.

## What next?
Create a web app where users can paste news, links or text and to get the results.
And the check if it is possible to integrated the fake news detactor on other platform as well to be able to flag news or articles as FAKE or REAL.

## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc

