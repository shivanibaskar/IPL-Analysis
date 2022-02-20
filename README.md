# IPL-Analysis

This project was done as a part of **SI618-Data Manipulation and Analysis** a course I took at the University of Michigan.

### MOTIVATION: 
Cricket is a bat-and-ball game played between two teams of eleven players on a field at the center of which is a 22-yard (20-metre) pitch with a wicket at each end, each comprising two bails balanced on three stumps [1].  Right from my childhood watching cricket and discussing about it has always been a part of my life. In India, cricket is not only considered as a game, but it is considered as an emotion. After watching this [video](https://www.youtube.com/watch?v=thql-9i9b1k) on YouTube a few months back I realized how the insights from data can help teams to form strategies to win a cricket match. The main reason why I chose this dataset is because I wanted to apply the skills that I learnt to the data from the league that I enjoy the most. I have used the data from the Indian Premier League(IPL).IPL is a T20 cricket league contested by  teams representing different cities in India. 

### DATA SOURCE: 
I have used the [IPL Complete Dataset (2008-2020)](https://www.kaggle.com/patrickb1912/ipl-complete-dataset-20082020) available on Kaggle. It contains ball by ball data and match wise summary statistic in two separates .csv files for all IPL matches played between the years 2008 and 2020. The ball-by-ball csv files contains about 193468 rows and 18 columns namely of which I will be using the columns of match id, the innings in which the ball was played, the runs scored in the ball and whether a wicket was taken in the ball. The match file contains about 816 rows and 17 columns of which I will be using the columns that contain the id of the match, the venue of the match, the two teams playing the match, the winner of the toss and the winner of the match. For some analysis joining of  both the .csv files for would be required.

### RESEARCH QUESTIONS: 
Main Question:
What are the factors that influence the match outcome for a team in the IPL?
1.	Does the team winning the toss have an advantage over the team losing the toss?
       *	Does the team winning the toss have a higher probability of winning the match?
       * 	Does the decision made by the team(to field or to bat first) after winning the toss have an impact on the outcome of the match?
2.	Does home advantage really play a role in the outcome of an IPL match?
3.	How does powerplay impact the outcome of the match?
      * The distribution of scoring elements in all the innings played by the winning teams vs the in all the innings played by the losing teams.
      * Association between the outcome of the match for the chasing team associated and the  percentage of the runs of the target they score during the powerplay.
      * Association between the winning probability of a chasing team and the scoring elements during powerplay.
