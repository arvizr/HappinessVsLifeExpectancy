## Google Slides - 
https://docs.google.com/presentation/d/1_1O2XrzdnD5bw3EybJFovG8bCT8X6GAH73JepdtmGqI/edit?usp=sharing

# Happiness vs Life Expectancy 

Presentation outline:

Our selected topic how happiness correlates with life expectancy, and an analysis of other impactful influences (suicide, GDP, and more).

The reason this topic was selected is because mental health has finally started to take precedence in our world. Our group wanted to show the impact happiness levels have on our life expectancy, and recommend investing in your personal happiness.

This data was sourced from the World Happiness Report which uses global survey data to report how people evaluate their own lives throughout the world. We chose to use 2018 as it was before the pandemic, to give the clearest picture of happiness results in a stable world.

Questions we hope to answer with the data:
How does happiness impact life expectancy?
Which countries are the happiest?
Which countries live the longest?
If a country was created in 10 years, what would their life expectancy be according to their happiness?

During the data exploration phase of the project, our group looked for initially apparent trends in data. One trend that we saw was that men and women had similar trends for happiness vs life expectancy. This helped us decide that we wanted to focus on countries as a whole, instead of separating by gender.

During the data analysis phase of the project, we employed a linear regression model to show the trends more specifically, and to give us a prediction of a country’s happiness versus life expectancy if it were to rise or fall. We also used our analysis to create a new country, “Dennysland”, and predict what our life expectancy would be for a reported happiness level.


## Communication Protocols
Our team has been in commmunication through Slack and class breakout rooms via Zoom. We also meet twice a week, one hour prior to class and discuss what we have researched and created, therefore we can use class time to work on the next segment of the project. 


# Machine Learning Process: 

Data preprocessing - as we chose a data set that is often used and maintained, not much preprocessing was needed. We did explore and make decisions as to which data points we would include, and how to group as needed.

Preliminary feature engineering and preliminary feature selection - we decided in this early stage that the graphs needed to be combined to create a stronger database for our work and to show the trends. The team did decide not to pull in external data, as we wanted to focus on happiness and life expectancy. There was some difficulty deciding which impacting features were most important to us.

Training and testing - we framed the model on 1/2 of our data to explore the trends, we chose happiness in women to train the initial model. Then we tested the model on the remaining ½, happiness in men, to show that the model would show similar trends to the source data. 


Model choice - we chose a linear regression as it would help us show the relation and predict future life expectancies, and life expectancy of a new country.
Benefits - linear regression is known to be the easier of the machine learning models, and our data had a strong trend so it worked well.
Drawbacks - linear regression really only tells one story.


# Dashboard:
Tools used -
Tableau
PGAdmin
SQL language

Interactive portion - Initially, we had discussed filtering between men and women, however the trends we saw in the initial exploration phase of the data showed that there was not a noticeable different. Next, the team decided it would be most impactful to be able to filter by country to show their statistics and let others explore our data world on their own. 

