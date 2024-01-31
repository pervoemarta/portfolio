# Aggregated study project

## Task 1: Analysing the bank's customer churn 
  
Analyse the customers of a regional bank and identify the customer segments who tend to quit the bank:
 
1. Data Examination, 
2. Data Pre-processing,
2. Exploratory Data Analysis (distributions of probability of customers leaving by attributes):
    + analysing customer activity (payment amounts, age of purchases, number of products used),
    + analysis of customer churn by attributes (gender, age, etc.),
    + segmentation by combined attributes (based on probability distributions of leaving)
3. Statistical Analysis:
    + hypothesis generation and testing.
  
### General summary:
The exploratory analysis identified the main parameters of users who leave:

- By number of products:
3 or more
- by ownership score:
from 5
- by activity:
active
- by gender:
М
- by credit card availability:
none
- by credit scoring:
642 points and above
- age group:
40 and over
  
By combining different attributes, we have found groups of 500-2000 customers that share common features.
This provides us with additional data, which we can use to avoid customer churn by monitoring and adjusting:

- men with credit scores of 642 and above,
- men with credit scores of 5 and above,
- users aged 40 and over with a credit score of 642,
- active customers who do not have a credit card.

### Assumption
We can see that, in general, all groups of departing users are connected with credit in one form or another:

- high scoring, indicating good creditworthiness: a male has repaid a loan quickly and on time, and no more credit is needed -- new loans with a more favourable rate can be offered to such men,
- men with high property scores are also more reliable and faster in repaying their obligations, possibly going to another bank with more favourable terms,
- all users with high credit scoring are faster than others to lose the need to remain a customer of a bank if there are more favourable terms at another,
- customers who have no credit cards (i.e. no obligations to the bank) tend to change banks more quickly if there are more favourable terms at competitors.

### Necessary
Ask potential quitting customers (from the groups found) what would be interesting, favourable for them, what makes them uncomfortable, why they might leave and other questions.



## Task 2: A/B test
  
Evaluate the results of the A/B test:  
1. evaluate the accuracy of the test:  
   + make sure there is no overlap with a competing test and no users participating in two test groups at the same time,  
   + check if the users are evenly distributed among the test groups and if they are formed correctly.
2. analyse the results.

### General summary:
Having checked all the data, we declare that the test has been prepared unsuccessfully.

- After preparing the data we can state that the test is successful in the sense that there is a result, but the duration of the test is incomplete, there is no data for 5 days (31 Dec - 4 Jan) and there are suspicions that the peeking effect occured, the test was finished earlier than planned, which is always for nothing.
The changes made for the test group did not bring results for conversions. Based on these results it is worth to think of alternative actions to increase conversion, but still conduct a full-fledged test (equalise the number of people and adjust the dates, run the test to the end. The test also crosses with the New Year's Eve promotion, which also has a separate impact on conversion without any innovations.
- In the initial raw data, there were extra users attracted after the end of the test enrolment period and who would not have "lived" the analysis horizon.
- Also, users from outside the target region were found in the data. The size of the groups differed greatly (the test group differs from the control group by one third).
- Also we should note that there are users participating in two competing tests at the same time, because of which there can be incorrect conclusions about what exactly influenced the conversion rate of specific clients. For example, judging by the name of the second test (interface_eu_test), maybe in that test there was an opportunity to buy immediately without going to the basket. Although there were few such crossed users, something interface-related could have a strong impact on conversions, more than some recommendation changes.

### Recommendations:
- upload data properly,
- correctly and evenly divide users into groups,
- run the test to the end,
- do not intersect participants with other tests,
- do not cross the test with promotions.

## Task 3: SQL using Jupyter  

1. Count how many books were published after 1 January 2000,  
2. For each book, count the number of reviews and the average rating,  
3. Identify the publisher that has published the largest number of books thicker than 50 pages - so you can exclude brochures from the analysis,  
4. identify the author with the highest average rating of books - only books with 50 or more ratings should be considered,  
5. calculate the average number of reviews from users who gave more than 48 ratings.

### General summary:
Using the results of the study, the following interesting observations can be brought out to create a new book reading app:

- Publish more books as our app has only 819 books since 2000, this is very few. If we have coronavirus times, it turns out that 819 books have been published in almost 20 years,
- keep in mind the ability to review and rate books, it's good practice and very helpful to have lots of reviews to see if a potential reader will like a book,
- look out for popular publishers who have a lot of books and they are highly rated, this will bring in more profit. However, do not forget about smaller ones, because for every book there will be a fan, this will help to get more users,
- be sure to have books by the most popular authors in the database, also for profit and a large number of users,
- ask readers in the app to rate the books they read, give bonuses or something like that, as reviews and ratings are great. However, in my opinion, a simple evaluation is not very informative, competitors do not sleep, so it is better to allow the evaluation with a comment, then there is a greater likelihood of a true evaluation, but this can then be investigated further.

--------
  
**Don't hesitate to reach me out:**  
![image](https://github.com/pervoemarta/yp_da_final/assets/155819108/8cf9026a-a0d3-44db-9e0c-0012562d53a8) - via LinkedIn,  
![image](https://github.com/pervoemarta/yp_da_final/assets/155819108/7422ccec-2be3-4c93-87c4-12a0b3660c84) - via Telegram.
