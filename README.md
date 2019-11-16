# IBM-Data-Science-Capstone-Project
RECOMMENDATION SYSTEM TO START A RESTAURANT BUSINESS IN LONDON

Article link: https://www.linkedin.com/pulse/recommendation-system-start-restaurant-business-london-mahalank

London is a megacity, the capital of the United Kingdom and one of the oldest of the world’s great cities, with its history spanning nearly two millennia. By far Britain's largest metropolis, it is also the country’s economic, transportation, and cultural center. The population of London had already exceeded one million by 1800 and it reached 9 million in 2018. London and the UK's population has one of the most diverse groups of origin countries in the world. Also, London is one of the world's leading tourism destinations with 21 million international visitors in 2018.

In recent years the restaurant industry in the United Kingdom and specifically London has undergone a period of growth. Consumer expenditure on restaurants and cafes reached close to £ 88 billion in 2017. The number of enterprises has been steadily increasing, contributing £ 17.9 billion to the British Economy.

Considering London's diversity and ethnicity it is evident that starting a restaurant business would earn you more money comparatively than most of the other businesses. Although, with more profitable business there comes the most competition. This article can serve as one of the guides to start a restaurant business based on a particular cuisine like Indian, Italian, American, etc., by providing a specific location. The number of restaurants in a specific location categorized based on cuisine and population distribution based on ethnicity and culture are some of the features considered for analysis.


Problem Definition:

A restaurant is a business which prepares and serves food and drink to customers in return for money, either paid before the meal, after the meal or with an open account. London is famous for its excellent cuisine. Its food culture includes an array of international cuisines influenced by the city’s immigrant history.
So, it is evident that to survive in such competitive market it is very important to strategically plan. Various factors need to be studied in order to decide on location such as;
1.	London Population and demographics 
2.	Who are the competitors in that location?
3.	Cuisine served / Menu of the competitors
4.	Are there any Farmers Markets, Wholesale markets etc. nearby so that the ingredients can be purchased fresh to maintain quality and cost? 
5.	Are there any venues like Tourist attractions, Entertainment zones, Parks etc., nearby where floating population is high
6.	Segmentation of the Borough
7.	Untapped markets
8.	Saturated markets etc. 
And the list goes on…
Even though well-funded XYZ Company Ltd. needs to choose the correct location to start its first venture. If this is successful, they can replicate the same in other locations. First move is very important, thereby choice of location is very important.

To build a recommendation model, following datasets and information are considered for analysis;
1.	Scrapped Wikipedia using BeautifulSoup, to extract information about 32 London boroughs also known as local authority districts. Also, considered local areas or neighborhoods for each borough for detailed analysis.
2.	I used Foursquare API to get information about available restaurants for a given neighborhood and borough in London. The API also provided information about restaurant styles based on cuisine.
3.	Employed data provided by the British Government from data.london.gov.uk to get more insights about London boroughs. The data provided knowledge about the population density, immigrants' country of origin and many more.


Results:

The results can be approached in two ways;
1.	If XYZ company wants to open a restaurant in preferred location and irrespective of cuisine, refer to that neighborhood in specific cluster and chose cuisine with the least common restaurant for better profits
2.	If XYZ company want to open a restaurant with a preferred cuisine and irrespective of location, refer to the cluster with the least number of restaurants with that specific cuisine and select one among the neighborhoods based on the company’s preference.

This analysis is performed on limited data. This may be right or may be wrong. But if good amount of data is available there is scope to come up with better results. If there are lot of restaurants probably there is lot of demand. London has so many restaurants, yet certain neighborhood or borough doesn’t have a specific cuisine restaurant available. 
As per the neighborhood or restaurant type mentioned like Indian Restaurant analysis can be checked. A venue with lowest risk and competition can be identified. 
