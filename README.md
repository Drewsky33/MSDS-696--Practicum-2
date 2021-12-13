# MSDS-696--Practicum-2

## Project Layout
* Final Project Notebook
* Project Presentation
* Project Paper
* Video Presentation

## Project Introduction

In this project, I built machine learning models to predict outcomes of a soccer match based on data accumulated over the course of a soccer season. 3 different models were used and evaluated for the classification problem. These included:
  * Logistic Regression
  * Support Vector Machine
  * Random Forest Classifier

The second part of this project was an age profile of the Big 6 in the English Premier League: Arsenal, Chelsea, Liverpool, Manchester United, Manchester City, and Tottenham Hotspur. 

## Research Questions

* What kind of match day data is important in predicting a winner of a match?
* What kind of players do champions usually have? (Age profile)

## Data Sources:

* The data used in building the model came from: http://football-data.co.uk/englandm.php 

* The data used for the age profile came from: https://fbref.com

##  Data Acquisition/ Preprocessing
* 10 datasets were collected from http://football-data.co.uk/englandm.php. These datasets were scraped, scrubbed, and new features were added to create additional datapoints that aided in the model build. Data was aggregated for each individual season and the datasets were all concatenated to use in the models. The final dataset had 23 features with 3799 points within those features. 


## Model Comparisons


![image](https://user-images.githubusercontent.com/77873198/145753228-3fc68b1d-d5ef-45e4-a144-0a7eed484abf.png)

## Further Evaluation

Logistic Regression performed the best of all the model with an f1 score of .6075, and an accuracy score of .66.

![image](https://user-images.githubusercontent.com/77873198/145753442-01750376-583f-46c5-a3aa-1b9635c0cb28.png)

## Big 6 Age Profile

I decided to profile the Big 6 because of the historical dominance of the 6 biggest teams in England. This is highlighted in the table below:

![image.png](attachment:24773b32-7126-4643-b6cc-906ac6aa7c81.png)
Image source: https://en.wikipedia.org/wiki/List_of_English_football_champions

![image](https://user-images.githubusercontent.com/77873198/145753773-3f34e375-a605-4922-b924-6584776ec31f.png)

## Conclusion

* What kind of match day data is important in predicting a winner of a match?

![image](https://user-images.githubusercontent.com/77873198/145754037-8090fab2-cb95-48ab-ac66-be92be8dbb27.png)


* What kind of players do champions usually have? (Age profile)

What was learned from the age profile was that teams that had players in the primes of their careers contributing more minutes tended to do better than teams who had large amounts of youth contributing quality minutes. 
* The top 4 of the league Manchester City, Liverpool, Chelsea, and Manchester United supported this idea. 
* Arsenal and Tottenham the other members of the big 6 didn't have the same amount of players in their primes logging meaningful minutes indicating an overeliance on youth and possible poor recruitment. 
