# nosql-challenge
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. I've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

# How I went about the challenege
To start, data containing various food establishishments was imported in and updated with a new restaurant that the magazine inquired about. Then, the data was cleaned a bit by updating strings of numbers into numeric data values. After cleaning the data, various documents were extracted and converted into dataframes such as one that highlighted the establishments with the lowest hygiene ratings and one that categorized the local authorities with the highest number of establishments with perfect hygiene score.


# Credit
When answering the third question in the analysis section of this challenge, I ran into trouble getting the correct documentation for what code I wanted to implement. The way I went about it kept producing results outside my filter - Tumisang from AskBCS learning assistant provided the sample code below, that illustrated the documentation for the questions approach. I tried my best to keep my code original and consistent to how I wanted to approach the question but the documentation is pretty much as they provided it.
Sample code:
query = {'geocode.latitude': {'$gte':latitude-degree_search, '$lte':latitude+degree_search},
         'geocode.longitude': {'$gte': longitude-degree_search, '$lte': longitude+degree_search},
         'RatingValue': 5}