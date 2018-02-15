# DataScienceProjects
This documents explainsbriefly short what each project code contains:

Exploring_Gun_Deaths: Skills involved - Python basics

In this project, you'll be working with Jupyter notebook, and analyzing data on gun deaths in the US. The data set can be found here - https://github.com/fivethirtyeight/guns-data

Summary of steps involved:

Removing the header data
Counting Gun Deaths By Year
Exploring Gun Deaths By Month And Year
Exploring Gun Deaths By Race And Sex

Findings
It appears that gun related homicides in the US disproportionately affect people in the Black and Hispanic racial categories

----------------------------------

thanks_giving_dinner: Skills involved - Numpy, Pandas

Steps:

Filtering Out Rows From A DataFrame
Using value_counts To Explore Main Dishes
Figuring Out What Pies People Eat

Findings: Although we only have a rough approximation of age, and it skews downward because we took the first value in each string (the lower bound), we can see that that age groups of respondents are evenly distributed

Correlating Travel Distance And Income

Findings: It appears that more people with high income have Thanksgiving at home than people with low income. This may be because younger students, who don't have a high income, tend to go home, whereas parents, who have higher incomes, don't.

Linking Friendship And Age.

Findings: It appears that people who are younger are more likely to attend a Friendsgiving, and try to meet up with friends on Thanksgiving.

-----------------------------------

Earning_based_on_stream_income: Skills Involved - matlib, Pandas

We analyse revenue earned by students based on the college major they have taken.

Steps:

Reading the data
Pandas, Scatter Plots
Pandas, Histograms
Pandas, Histograms
Pandas, Bar Plots

Findings: The plots give an easy to understand view for data comparison between different majors.

---------------------------------

Visualizing_gender_gap_degrees: Skills - matlib, Pandas

We analyse the gender gap in college majors using graphs, cleaning the plot for better stark comparisons.

Steps:
Reading the data sources
Comparing across all degree categories
Hiding x-axis labels
Setting y-axis labels
Adding a horizontal line
Exporting to a file

---------------------------------

NYC_Schools_DATA: skills involved - Data cleaning skills, numpy, pandanas, matlib

steps:

Read in the data, Read in the surveys, Add DBN columns
Convert columns to numeric, Condense datasets, Convert AP scores to numeric
Combine the datasets, Add a school district column for mapping,Find correlations
Plotting survey correlations

Findings:

It is more interesting that rr_s, the student response rate, or the percentage of students that completed the survey, correlates with sat_score. This might make sense because students who are more likely to fill out surveys may be more likely to also be doing well academically.
How students and teachers percieved safety (saf_t_11 and saf_s_11) correlate with sat_score. This make sense, as it's hard to teach or learn in an unsafe environment.

Exploring safety: Looks like there are a few schools with extremely high SAT scores and high safety scores
Plotting safety

Racial differences in SAT scores: higher percentage of white or asian students at a school correlates positively with sat score, whereas a higher percentage of black or hispanic students correlates negatively with sat score.

Gender differences in SAT scores:cluster of schools with a high percentage of females (60 to 80), and high SAT scores.

--------------------------

 star_Wars: pandas, numpy, matlib
 Does the rest of America realize that “The Empire Strikes Back” is clearly the best of the bunch?

Steps:
reading and cleaningthe data
finding the mean for plotting for star wars column
Plot rankings Findings: original" movies are rated much more highly than the newer ones.
View counts PLot: original movies were seen by more respondents than the newer movies.The earlier movies seem to be more popular.
Male/Female differences in favorite Star Wars movie: more men watched 1-3, but less males liked them than females.

---------------------------------

Analysing_Movie_Review: Statistics Concepts - mean, median, standard Deviation, linear regression, matlib for plots, pandas, numpy

Analyse scores based on critic ratings

steps: Read data, normalize the data for easier review process

Fandango vs Metacritic Scores: The Fandango reviews also tend to center around 4.5 and 4.0, whereas the Metacritic reviews seem to center around 3.0 and 3.5.

Fandango vs Metacritic number differences: Fandango ratings in general appear to be higher than metacritic ratings

The median metacritic score appears higher than the mean metacritic score because a few very low reviews "drag down" the median. The median fandango score is lower than the mean fandango score because a few very high ratings "drag up" the mean.

Fandango inherently uses a different rating system.

Finding Residuals: linear regression plot

--------------------------------------------
Winning_Jeopardy: skills- Probability, Chi-squared tests

Jeopardy is a popular TV show in the US where participants answer questions to win money.
we work with dataset of Jeopardy questions to figure out some patterns in the questions that could help you win

steps:

read data, clean data
Find answers appearing in question: The answer only appears in the question about 6% of the time. This isn't a huge number, and means that we probably can't just hope that hearing a question will enable us to figure out the answer

Question overlap: 70% overlap with old questions, we must go through old questions.

Chi-squared results:None of the terms had a significant difference in usage between high value and low value rows. Additionally, the frequencies were all lower than 5, so the chi-squared test isn't as valid. It would be better to run this test with only terms that have higher frequencies.

---------------------------------

Predicting_Car_Prices:  fundamentals of machine learning using the k-nearest neighbors algorithm

The data set we will be working with contains information on various cars. For each car we have information about the technical aspects of the vehicle such as the motor's displacement, the weight of the car, the miles per gallon, how fast the car accelerates, and more.

Steps: 
Reading data
cleaning the data for normalisation - remove null values
univariate k-nearest neighbors model - for further structuring work flow
multivariate models














