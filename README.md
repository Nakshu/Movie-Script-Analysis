# Movie-Script-Analysis
## Overview

Movies are cultural art created to represent various cultures. It is considered to be an important art form that not only provides entertainment but also historical value. It is one of the biggest mediums of communication between different parts of the world. This code will create a dataset which will help them figure out the cause of a failed movie or the reason for success. This project will be useful for the movies with franchises like Harry Potter, Twilight, Starwars, and Marvel, where a director can take the input from the summary sheet and implement in the next part of the movie.
## Description

This document contains the complete information on data acquisition and data analysis for a movie script analysis. 
#### Data Acquisition: 
The data is scrape from two sources – a movie scrip and IMDB website
-	A movie script is used to create a dataset having columns speaker and their respective dialogue.
-	From IMDB website, a dataset is created with all the reviews and ratings given to the movie 

#### Analysis: 
We are aiming to provide recommendation to the directors and producer based on the viewers response towards the movies. It will help them know how to make the next film better than the previous one. We will perform sentiment analysis on both the datasets acquired in the earlier stage.

We have taken “Twilight” – 2008 movie as an example to perform our analysis. Twilight is a 2008 American romantic fantasy film based on Stephanie Meyer's 2005 novel of the same name. Directed by Catherine Hardwicke, the film stars Kristen Stewart and Robert Pattinson. It is the first film in The Twilight Saga film series. Based on 219 reviews collected by Rotten Tomatoes, the film has a rating of 49% and a weighted average score of 5.41/10.
## Getting Started

### Dependencies
- We have used Jupyter Notebook V6.4.5. This code can be run on any platform 
- Libraries required for the code are: 
            1.	csv                   7.wordcloud
            2.	pandas                8.numpy
            3.	matplotlib            9.scrapy
            4.	seaborn               10.selenium
            5.	plotly                11.time
            6.	nltk                  12.tqdm
                                      13.warnings

### Installing
- Make sure the script is in text format
- These libraries can be installed in notebook by running 
        pip install <library name>
  ## Challenges and Limitations

The challenges faced during the project development are:

- We converted pdf to text file to get the exact dialogue by preserving the whitespaces in the script.
- The sentiment analysis is limited to dialogues spoken by character and the characters through out the movie but not for each scene as we were not able to extract review related to scenes as mentioned in the project scope.
- The sentiment analysis is based on the speaker but not on the conversation between speaker and listener which might vary from the current analysis. Hence, a future improvement can be to extract listener column as well from the script. 
- Considered review from only one source (IMDB) based on the run-time. Some of the rating websites like rotten tomatoes doesn't make their information readily available which results in longer run-time.

The code and the results of this project are available in this repository. Feel free to use the code for any purpose and give credit where it's due.
