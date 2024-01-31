# Aggregated project - 2
Work with the sales funnel using **pandas**, **datetime (including timedelta)**, **matplotlib (including pyplot)**, **numpy**, **scipy**, **math**, **plotly**.

## Research on the user behaviour of a mobile app (startup) selling food products
- research of the sales funnel,  
- detailed analysis of the users' path to purchase (conversion),  
- analysis of the results of the A/B test (changing the font in the app).

### General summary:  
We created an event funnel consisting of 4 steps (MainScreenAppear, OffersScreenAppear, CartScreenAppear, PaymentScreenSuccessful), the 5th event (Tutorial) we excluded from the funnel due to the lack of a consistent relationship with the other events. The conversion of the above sequence was defined as:
from event A to B - 61.9%,
from event B to C - 81.3%, from event C to D - 94.8%. The conversion from A to D was 47.7%.

We examined the results of the AAB tests and performed a total of 16 experiments (4 groups of 4 subgroups), adding a 4th combined control group.
The results of all experiments showed that there was no reason to consider the difference between the criteria significant. When conducting the tests, we chose the standard critical significance level of 5% due to the absence of concerns about errors of the first kind on the background of high p-value.

**The main objective of the study:** to find out the impact of the new font on the site. According to the results of the study we make a conclusion that changing the font will not change the sales volume and other financial indicators.
We can draw the attention of the startup's marketing department to the conversion rate from the home page to the catalogue. It may be worth working on the homepage and the convenience of links for viewing product pages.

We recognise the test as successful, however, it is necessary to formulate and test other hypotheses.
