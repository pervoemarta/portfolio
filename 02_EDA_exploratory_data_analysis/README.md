# Exploratory Data Analysis
Сompile portraits of users using **pandas**, **plotly**, **seaborn**, **matplotlib**

## Research of flat announcements for sale.  
We have data from the Yandex.Real Estate service - an archive of advertisements for flats for sale in St. Petersburg and neighbouring settlements for several years. We need to learn how to determine the market value of properties. Our task is to set the parameters. This will allow us to build an automated system: it will track anomalies and fraudulent activity.

For each flat for sale, two types of data are available. The first is entered by the user, the second is obtained automatically on the basis of map data. For example, the distance to the centre, airport, nearest park and water body.  

### General summary:
We did a lot of work: we got a spreadsheet with various manual typos, incorrect data types, missing values, and values that were not sufficient to fulfil our tasks. By logical reasoning, we filled in the blanks where possible, corrected typos, removed anomalies added data and got answers to the questions posed. Interesting patterns of price per square metre of area were detected, the information is given conveniently, in tables and graphically. The general conclusion on property sales in St. Petersburg is as follows:

The most common adverts where:

- the average area of flats for sale is about 50 square metres,
- the average living area is slightly less than 30 square metres. m,
- the area of the kitchen 9 square metres,
- average cost of 4.6 million rubles,
- 2 rooms,
- height of the ceiling 2.65 m,
- apartment on the 4th floor in a 9-storey building,
- 13 km to the centre,
- parks and ponds in walking distance.

It was also found that flat ads are hard work, so most likely working people post their property on weekends, and realtors work all week. It has been noticed that the placement of adverts is subject to generally accepted holidays and vacations (summer, New Year). It is quite difficult to judge the time of placing an announcement, because Yandex.Real Estate has rules that remove ads on certain days. We found that the cost of the object is affected by the area (total, living, kitchen), number of rooms, proximity of parks and water bodies, although this information is not very full. The ground floor has always been and remains the cheapest, then the last floor, then all the others. Also be sure to send information about missing values and typos to colleagues to make it so that there are fewer of them. Very interesting project, a lot can be learnt, calculated, found out from standard data.
