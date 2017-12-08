# Project : Create a Tableau Story

Dataset used : Titanic-dataset

***

## 1. Link to the Tableau stories made

[My Tableau public profile](https://public.tableau.com/profile/jeswin.george#!/)

## 2. Summary
The data visualization made tends to explore the survival chances of passengers aboard the Titanic. The graphs show the survival chances depending upon gender, age, port from which the person embarked and passenger class. I have also explored the age and and price fare of passengers aboard the Titanic and tried to relate the survival according to it.

## 3. Design

Created a new dimension ```Survived_TF``` which has boolean values to denote whether a person has survived the tragedy or not. Created another dimension ```Adult-Child``` which classifies people as _Adult_ or _Child_ based on their age  whether its above or below the age of 18 using calculated-field.  

Made a hierarchy named ```Passengers``` which has two levels _Gender_ followed by _Adult-Child_.  

For visual encoding i have used __red color__ to denote people who did not survive the tragedy and __blue color__ to denote people who survived.  

In the project i used stacked and side-by-side bar-graphs to classify the data based on different dimensions such as gender, port from which the passenger embarked and class to which the passenger belonged aboard the Titanic. Also i have stacked the bar graph to show whether the passenger has survived or not.   

The stacked histograms gives an idea of range of age passengers who were mostly onboard the Titanic and how many of them survived. I have also used the above histograms to explore the price fare of the passengers.

 

## 4. Feedback 

Feedback collected from two persons : my Udacity mentor and a friend.  

 
> The first graph was very compact and illustrative in the sense that it clearly shows two things: 1. total men is larger than total women, 2. the survival rate diff between women and men is very different. I like the first graph. The second graph is kind of heavy to read, the name of ports is better read if put below the x axis, so that info is not scattered around the graph, same applies to Pclass/Sex plot. The summary for the Age histogram is kind of weak, I didn't know after reading the comments what observation you had there. overall you did a good job on this visualization project, generally easy to read, and I had the impression that men had lower survival rate than women, class 3 survival rate lower than 1&2, and survival rate is also related to age.
and I like the coloring too. Red means not survived, green means survived is really intuitive to me and I like your using stacked histogram to add another dimension to do comparison(i.e. survived vs not survived within sex).

> Can define an additional dimension classifying the passengers as child/adult to see their survival chances.



## 5. Resources

1.  [Free Training Videos](https://www.tableau.com/learn/training) from Tableau
2.  [Tableau Documenttation](http://onlinehelp.tableau.com/current/pro/desktop/en-us/help.htm)
    



