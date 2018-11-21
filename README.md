# Kickstarter
A dataset that required high maintenance through cleaning and EDA

Kickstarter is an American public-benefit corporation based in Brooklyn, New York, that maintains a global crowdfunding platform focused on creativity and merchandising. The company's stated mission is to "help bring creative projects to life". Kickstarter has reportedly received more than $1.9 billion in pledges from 9.4 million backers to fund 257,000 creative projects, such as films, music, stage shows, comics, journalism, video games, technology and food-related projects.
People who back Kickstarter projects are offered tangible rewards or experiences in exchange for their pledges. This model traces its roots to subscription model of arts patronage, where artists would go directly to their audiences to fund their work.

I found this dataset on kaggle and when I went through the data, I thought of making a prediction model which classifies the data by, if a project is successful or not. The dataset needed a lot of cleaning to be done. I have shown my approach to this project step by step below.

### Exploratory Data Analysis (EDA)

I used Tableau to visualize and understand this dataset. I will then use this insight to add or remove features for predicting the outcome.

**1. Percentage of success**

![](Images/1.png)

- The image shows that a project is 2 times more likely to fail than to succeed.

**2. Pledged, Goal**

![](Images/2.0.png)

- More users who have pledged more have succeeded and more users who've had higher goals have failed.

**3. Country**

![](Images/3.0.png)

- People from 'No' or Norway have a higher success to failure ratio than the other countries. To reduce the variables in countries, we can merge certain countries with less number of occurences togeather.




