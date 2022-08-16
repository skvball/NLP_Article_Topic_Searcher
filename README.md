# NLP_Article_Topic_Searcher
A file using NLP to extract specific information from hundreds of articles and sorting them by relevance to a certain chosen topic.

# Purpose
During my summer virtual internship to a political science journalist, I was tasked with sorting through 50+ emails- each with 150+ articles- to find articles relevant to her research. Instead of using command-f on each article and doing it manually, I coded this file in order to complete this process automatically and save time. This file will input a huge number of article links, search the article text for specific keywords, and keep relevant links while discarding the remaining links. Additionally, it creates sample summaries of the text- which is included in a separate column in the pandas dataframe. 

# How to read
The .ipynb file has all the instructions needed to use the file I created. 

# Software and Language
I used Python in a Google Colaboratory notebook, and- after a lot of research on article scrapers- I used the newspaper3k package to extract information from articles.

# Challenges
This entire project was a struggle as it was my first experience with NLP. However, I view my two biggest challenges as: unable to create an actual model that could create better summaries; and limited time to accomplish this project. 

# Accomplishments
This entire project was a struggle, as it was my first experience with NLP, so I took a long time even to get to this stage. But I am super proud of being able to research and figure out that I needed to use an "article scraper" and to manipulate and play with "abstract article summarization". I view getting here as an accomplishment, since I now know exactly what I need to use and research to expand this project.

# What's next
I plan on playing with the sample summaries I created and then test them to summaries I manually create- building a NLP abstract article summarization model. 
