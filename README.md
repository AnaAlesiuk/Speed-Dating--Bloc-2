# Speed-Dating
Exploratory, descriptive and inferential analysis of data

my email: anastasia@phiskills.com

video-explanation: https://youtu.be/OnhX1slarRM


## Goal

The goal of this project is to understand what happens during speed dating and especially to understand what will influence the obtaining of a second date.

## Exploring Data

So, as usual, the first step is to read the CSV file with our dataset. We have a lot of different columns, and thanks to the documentation file we can learn what each one of them mean. 

That is how, according to the column“iid,” we see that there are 552 participants.

As an analyst, I decided what question we should ask to understand what is important to obtain a second date.


## *What are the three most popular fields of study during speed dating?*


By using functions like group by, sum, and sort_values, we can count all the fields that the participants are from.  It seems that during the speed dating research the most popular fields of study among students were Business, MBA and Social Work. And the most rare were MFA Poetry, Fundraising Management, Sociology and Education.


## *Did most people get the date after speed dating or not?*

According to this bar chart, people mostly did not get dates after Speed Dating night. 
To go deeply into understanding what was the cause of getting the date, I created a data frame that was filtered by those who got the date.


## *Who was more likely to get the date?*

Looking at this bar chart, the majority of women who got the date were around 26 years old, and the majority of men who got the date were around 25 years old. The least likely to get the date was for women at 32 and men at 33.
 

## *What is the most common goal at the first step for men and women?*

According to this scatter plot, we see that for the majority of people who got the date after all, the goal of the speed dating "Seemed like a fun night out", but those who chose this option were women from 25 to 30 years old. Mostly men were choosing as a goal for speed dating "To meet new people”.

To compare the goal with those who did not get the date, I created another data frame, but this time by filtering people without a date.

And looking at this graph a lot of men who was planning to have a "fun night out" and women who wanted to meet new people didn't get a date at the end.


## *At what age is it more likely to get a date?*

Looking at this pie chart, we can analyze the ages of the people who got the date. The highest was 13,1% - people at the age of 27; there were 196 who got the date. Then - people at age 26 - 11,7%, and 10,1% for the age 23. So, approximately people from 23 to 27 years old are more likely to get a date.

And now to compare how old people who did not get a date I made a pie chart that shows that the age was mostly between 23-27.

In conclusion, as the age for those who got a date and those who didn’t is the same, we can say that this was the approximate age in general to participate in Speed Dating.


## *Was 4 minutes to meet a new person enough for participants?*

With the help of seaboard’s catplot we see that the majority of participants weren’t satisfied with the duration of the date, as it’s not enough to understand if you want to meet this person again or not


## *What attributes were important for making a decision?*

To answer this question, I created a new data frame where I included columns from the main data frame like the decision of partner the night of the event, age of partner, race of partner, and rating by partner the night of the event for all six attributes and their goal.

After that, I made a correlation matrix to see what influences a partner's decision. According to it, the most important of the indicators that I chose was rating by partner the night of the event for all 6 attributes.

Next, I wanted to see deeply what attributes were important for those who got the date. For that, I created a data frame with such values as attractive, sincere, intelligent, fun, ambitious, and shared interests/hobbies. From all the attributes that there were participants preferred ambitious people, and the least important was attractiveness.


