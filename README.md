[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/68QrIsnN)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=15339378)


# HACKATHON GROUP 5 PROJECT

## PROJECT TOPIC
Sentiment Analysis of real-world human interaction from social media using Python, NLTK, scikit-learn, and textblob

## DATASET USED
A compilation of social media posts, tweets, and text interactions inclusive of their Timestamps, Likes, Country, Platform etc. For the purpose of simplicity and speed our team of adept python developers decided to use the Text column in our Analysis.

## NECESSARY TOOLS TO RUN PROJECT
1. Python installed on your local machine
2. Install all the given dependencies (nltk, numpy, pandas, textblob)

## HOW TO RUN PROJECT
1. Clone the repository
2. cd into the directory
3. Run jupyter notebook or use google colab

## INFERENCES MADE
After plotting the polarity of the various social media tweets and posts, we arrived at a conclusion that on the 15th day of January, 2023 in the United States of America, United Kingdom, and Australia, a large majority of individuals were calm and neutral. Based on the dataset, we can deduce that these sampled individuals did not encounter any form of negativity which postulates that they did not experience occurences like Natural disasters, wars, hunger, etc.  The same can be said about a non-existent cause for celebration or high positivity or excitement.

To back the above claim based on the analysis of sentiments in the dataset provided, we plotted a scatter plot of the polarities (positive-neutral-negative bias) against the subjectivity (the balance between the objectivity and subjectivity of each statement) of the tweets, posts, and conversations made on social at that specific timeline.

Looking at the scatter plot visualized, the closer a statement is plotted to 1 on the polarity scale (xLabel), the more positive it is. The closer it is to 0, the more neutral, and the closer it is to -1, the more negative.

On the subjectivity scale (yLabel), the closer a statement is to 0, the more objective (governed by logic) it is, and the closer the statement is to 1, the more subjective (governed by a degree of emotion) it is.
