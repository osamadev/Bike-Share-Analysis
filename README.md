In this project, I will perform an exploratory analysis on data provided by Motivate, a bike-share system provider for many major cities in the United States. I will compare the system usage between three large cities: New York City, Chicago, and Washington, DC. I will also see if there are any differences within each system for those users that are registered, regular users and those users that are short-term, casual users.

## General Insights from this dataset
-  The city that has the highest number of trips is NYC (276798).
-  The city that has the highest proportion of trips made by subscribers is NYC (88.84%).
-  The city that has the highest proportion of trips made by customers is Chicago (23.77%).
-  Average trip duration for the three cities as follows: {Washington: 18.93 minutes, NYC: 15.81 minutes, Chicago: 16.56 minutes}
-  Porportion of rides in each city long than 30 minues as follow: {Washington: 10.84% , NYC: 7.3% , Chicago: 8.33% }

-  In Washington city I found that customers took longer rides on average compared to the subscribers. The result was as follows: {'Subscribers Avg. Duration': 12.53 minutes, 'Customers Avg. Duraion': 41.68 minutes}. 
-  The subscribers average trip duration is 12.53 minutes while the customers average trip duraion is 41.68 minutes which is really much longer then the subscribers average duration (more than three times).

## Investigate the dataset by asking questions that have answers in the data

**-  How the ridership volume changes across the different months for the different user types (Subscribers & Customers)?**
From the exploration and the visulaization in my jupyter notebook, the conclusion was the ridership volume for both user types generally reaches the highest values during the summer season, and also still quite high in the spring and fall seasons, but it goes down for both user types in winter. Also the proportion of the subscribers all the year is much higher than the customers. 

**-  How the ridership pattern differs for the subscribers and the customers during the days of the week? What week days have the highest ridership volume either for subscribers or customers?**
For this question, our investigation and analysis in the jupyter notebook code cells show clearly that the highest volume for the subscribers is during the week days or business days (from Monday till Thursday) and this volume reaches the highest peak in Tuesday and Wednesday for the subscribers. 
For the customers, the story is completely different, the highest ridership volume is during the weekend days (Saturday and Sunday) and it is low during the business days. The nice conclusion here is the customers usually use the service for fun and may be to do exercise :)
