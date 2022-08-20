# Capstone_Project
### Project Title
Sentiment Analysis for Under-Resourced Language
**Author**
Youngsahng Suh
#### Executive summary
A large multinational corporation is seeking to automatically identify the sentiment that their customer base talks about on social media. They would like to expand this capability into multiple languages. Many 3rd party tools exist for sentiment analysis, however, they need help with under-resourced languages. GOAL: Train a sentiment classifier (Positive, Negative, Neutral) on a corpus of the provided documents. My goal is to maximize accuracy.

#### Rationale
Why should anyone care about this question?
There is special interest in being able to accurately detect negative sentiment in social media comments. The training data includes documents from a wide variety of sources, not merely social media, and some of it may be inconsistently labeled. By correctly labeling them, companies could utilized these sources for the under-resourced languages. 

#### Research Question
What are you trying to answer?
Train a sentiment classifier (Positive, Negative, Neutral) on a corpus of the provided dataset below. Maximize accuracy of the classifier with a special interest in being able to accurately detect negative sentiment.

#### Data Sources
What data will you use to answer you question?
This dataset is authored by Zareen Sharf, from Shaheed Zulfiqar Ali Bhutto Institute of Science and Technology (SZABIST). Data set contains sentences in Urdu languate and it is tagged for sentiements either, Positive, Negative, or Neutral.
Sentences in Urdu are written in plain English for word processing rather than native Urdu fonts. Data includes documents from a wide variety of sources, not merely social media, and some of it may be inconsistently labeled.

#### Methodology
What methods are you using to answer the question?
Sentiment analysis involves the following stages:

    Loading and cleaning the data
    Exploratory data analysis
    Ommiting stop words or common words
    Creating new features
    Plotting most frequently used words
    Vectorizing sentences to build a matrix
    Training and testing the machine learning model
    Evaluating the machine learning model accuracy

#### Results
What did your research find?

Although our goal is to maximize accuracy, bias and variance are other important factors to consider since our focus is on an under resources language and also adequately detecting negative sentiment without being biased.

There are over 6900 languages in the world today and only a small fraction offers the resources required for the implementation of Natural Language processing or Human Language Technologies.

However, most technologies are concerned with the language for which large resources are available or which have suddenly become of interest because of economic and political science. Unfortunately, most languages from the developing countries received only a little attention so far. One way we intend to improve the language divide is by building Natural Language applications.

About 99% of the dataset is written in Hindi and the other 1% is in English. After effective cleaning and preprocessing, an intensive approach was taken toward the sentiment and I found that most texts sentiment are neutral. Furthermore, a word cloud technique was done.

After an effective data preprocessing and feature engineering, the high performance model with Bias and variance tradeoff was built with Logistic Regression Algorithm witth the test accuracy of 95% and test accuracy of 65%. However, our goal is to improve on the model overtime as more data are been feed into it.

Apparently, with the result from the high-performance model with bias and variance trade-off, more data are required to increase the accuracy and optimize the model.

This limitation can be address in large using data collection techquies, such as survey/questionaire, scraping of text written in hindi from social media, traditional data collection and deep learning apporach to improve the model accuracy, also.

#### Outline of project

- [Link to notebook](https://github.com/masterj7874/Capstone_Project/blob/main/Sentiment%20Identification.ipynb)

##### Contact and Further Information
