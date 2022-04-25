# Winning-Jeopardy

#### **Context and goal:**

Jeopardy is a popular TV show in the US where participants answer trivia to win money. Participants are given a set of categories to choose from and a set of questions that increase in difficulty. As the questions get more difficult, the participant can earn more money for answering correctly.

In June 2019, contestant James Holzhauer ended a 32-game winning streak, just barely missing the record for highest winnings. James Holzhauer dedicated hours of effort to optimizing what he did during a game to maximize how much money he earned. To achieve what he did, James had to learn and master the vast amount of trivia that Jeopardy can throw at the contestants.

Let's say we want to compete on Jeopardy like James. As he did, we'll have to familiarize ourselves with an enormous amount of trivia to be competitive. Given the vastness of the task, is there a way that we can somehow simplify our studies and prioritize topics that appear more often in Jeopardy? 

#### **Dataset:**

In this use case, we'll work with a dataset of Jeopardy questions to figure out some patterns in the questions that could help us win.  
the dataset is named jeopardy.csv and contain a subset of 20000 rows from much larger dataset of Jeopardy questions. Here's the beginning of the file:  

![jeopardy.csv](/Users/Aylan/Documents/IT/DataQuest/R/Winning Jeopardy/Jeopardy.JPG).

Each row represents a single question from a single episode of Jeopardy. Crucially, we can see the different question categories that appeared on a particular episode, the questions and answers themselves, and the value associated with the question.

**Note:** This code was written on RStudio.  
**Language:** R.  
**Packages:** readr, dplyr, stringr, tidyr, tibble.  
