# Analysing A/B test results, business decision-making
This project is conducted with the marketing department of a large online shop. I analysed A/B test results using **pandas**, **numpy**, **matplotlib**, **seaborn**, **scipy**.

## Increase the revenue of an online shop
The shop wants to increase the revenue, for a clear strategy a research is required.  

### The research will involve the following steps:  
- prioritisation of hypotheses,
- running an A/B test,
- analysing the results of the test.  

### General summary
Having analysed the results of the A/B test, we have the following:

- P-value on average number of orders on raw data did not reach statistical significance - statistically significant differences are present (we reject the null hypothesis). We also know that the benefit on the average number of orders of group B is 13.8%.
- P-value of the average cheque on the raw data is strongly greater than 0.05, so there are no stat. significant differences. However, it is worth bearing in mind that the average receipt of group B is larger than the average receipt of group A by 25.9%.
- Taking into account the anomalous data, we can conclude that even the statistical significance on the average number of orders reports the presence of important statistical deviations. In the cleaned data, the average number of orders per visitor of group B is greater than the average number of orders per visitor of group A by 14.8%.
- Anomalies in the average receipt do not report the presence of important statistically significant differences, but in average receipts over 30 000 moneys the advantage is on the side of group A by 2%.  

The graph of differences in average order quantity indicates the good data of group B and the continuation of its upward trend.  
The average receipt difference graph showed the dominance of the size of the average receipt by group B, especially if anomalies are not taken into account. The trend goes down towards the end of the test, but still at a good level of 25.9%.

The decision is to stop the test and admit the victory of group B.

The marketing department will be given priority hypotheses and advised to implement them, these are the following hypotheses:

- Add a subscription form to all main pages to gather a customer base for email newsletters.
- Add two new channels to attract traffic, which will attract 30% more users.
- Launch a promotion that gives a discount on a product on its birthday.
- Add product recommendation blocks to the website of the online shop to increase conversion rate and average order receipt.
- Show banners with current promotions and sales on the homepage to increase conversion rates.
