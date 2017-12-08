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

For visual encoding i have used __blue color__ to denote people who did not survive the tragedy and __orange color__ to denote people who survived.  

In the project i used stacked and side-by-side bar-graphs to classify the data based on different dimensions such as gender, port from which the passenger embarked and class to which the passenger belonged aboard the Titanic. Also i have stacked the bar graph to show whether the passenger has survived or not.   

The stacked histograms gives an idea of range of age passengers who were mostly onboard the Titanic and how many of them survived. I have also used the above histograms to explore the price fare of the passengers.  


Based on the feedback received, i made the following changes to my Tableau story :

- In the story points 3 and 4, i put the label of name of ports and passenger class below the x-axis as it increases the readability of my story.
- Edited the summary of the story point related to the age histogram.
- Defined an additional dimension ```Àdult-Child``` which can give better insight into the passengers who survived the tragedy.
- Changed the red-blue color palette which i had used earlier to blue-orange color palette as they are more  color-blind friendly colors.
- Instead of using "% of Total Number of records" as a label, i replaced it with "% of Total Number of Passengers" to give more clarity
to the visualization.

 

## 4. Feedback 

Feedback collected from : my Udacity mentor, a friend and Udacity project review.  

> The first graph was very compact and illustrative in the sense that it clearly shows two things: 1. total men is larger than total women, 2. the survival rate diff between women and men is very different. I like the first graph. The second graph is kind of heavy to read, the name of ports is better read if put below the x axis, so that info is not scattered around the graph, same applies to Pclass/Sex plot. The summary for the Age histogram is kind of weak, I didn't know after reading the comments what observation you had there. overall you did a good job on this visualization project, generally easy to read, and I had the impression that men had lower survival rate than women, class 3 survival rate lower than 1&2, and survival rate is also related to age.
and I like the coloring too. Red means not survived, green means survived is really intuitive to me and I like your using stacked histogram to add another dimension to do comparison(i.e. survived vs not survived within sex).

> Can define an additional dimension classifying the passengers as child/adult to see their survival chances.  

> Red-Green colors are not a good choice for using in comparisons since they are not color-blind friendly colors. The people with this disorder are not able to distinguish this two colors.  

> Don't recommend using "number of records" as a label. Instead, we can replace "records" with our target attribute like "survivors". This can make the visualization more clear.



## 5. Resources

1.  [Free Training Videos](https://www.tableau.com/learn/training) from Tableau
2.  [Tableau Documenttation](http://onlinehelp.tableau.com/current/pro/desktop/en-us/help.htm)
    



