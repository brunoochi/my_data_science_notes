# PJ Battle
This project uses basic NLP (natural language proecessing) techniques to analyze customer reviews of 4 well known first-person shooting games: Battlefield 5, Battlefield 1, Call of Duty Black Ops 4, and Call of Duty Inifinite Warfare.  

First, I use scrape the data from metacritic.com and store the data into pickle files.<br>
Second, I tokenize customer reviews using the Spacy library and visualize word occurrences using bar charts, wordclouds, and network graphs.<br>
Third, I load nltk library and perform sentiment analysis. The goal is to check how the tone of customer reviews changed over time.<br>
Fourth, using sklearn NLP capabilities, I conduct topic analysis to understand what are the dicussions points raised by Battlefield 5 reviewers.  <br>

- Check commented notebook:  [Part 1](PJ_Battle.ipynb)

![pj_battle_network.jpg](pj_battle_network.jpg)
