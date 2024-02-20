### Zomato-EDA

#### Overview:

Zomato API Analysis is one of the most useful analyses for foodies who want to taste the best cuisines of every part of the world which lies in their budget. 
This analysis is also for those who want to find value-for-money restaurants in various parts of the country for their cuisines. Additionally, this analysis caters 
the needs of people striving to get the country's best cuisine and which locality serves that cuisine with a maximum number of restaurants.

I am fascinated by good quality food being served in restaurants and would like to help the community find the best cuisines around their area.


#### About this dataset:

The collected data has been stored in the Comma Separated Value file Zomato.csv. Each restaurant in the dataset is uniquely identified by its Restaurant ID. 
Every Restaurant contains the following variables:

• Restaurant ID
• Restaurant Name
• Country Code
• City
• Address
• Locality
• Locality Verbose
• Longitude
• Latitude
• Cuisines
• Average Cost for two
• Currency
• Has Table booking
• Has Online delivery
• Is delivering
• Switch to order menu
• Price range
• Aggregate Rating
• Rating color
• Rating text
• Votes


#### Questions:

•	Top 3 Countries that use Zomato based on transactions.

•	Find the country name that has given a 0 rating (Have not given a rating).

•	Find out which currency is used by which country.

•	Which countries do have online delivery options?

•	Which countries have and do not have online delivery options?

• Top 5 cities distribution based on who ordered the most from Zomato

•	Derive some observations based on ratings from the dataset

•	Derive some observations based on the top 10 cuisines


#### Observations:
• Zomato's maximum records or transactions are from India (94.39%) because Zomato's main base is in India. Then the second-highest transactions are from the United States (4.73%) and the third-highest transactions are from the United Kingdom (0.87%)

• When the Aggregate Rating is between 4.5 to 4.9 [inclusive], it indicates that it is **Excellent**  & when the Aggregate Rating is between 4.0 to 4.4 [inclusive] it indicates that it is **Very Good**

• The "Not Rated" rating count is very high & the maximum number of ratings is between 2.5 to 3.4

• Maximum Number of 0 ratings are from Indian customers (2139 out of 2148)

• Online deliveries are available only in India and the UAE

• Maximum Number of transactions is from New Delhi (68.87%) [in terms of City]. The second highest transactions are from Gurgaon (14.07%)

• North Indian Cuisine is the most liked Cuisine on Zomato & Bakery, Desserts and Street Food do not have much popularity among Zomato users.
