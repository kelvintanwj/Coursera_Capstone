# Capstone Project: Capturing customer demands

This is a repo containing my work for the `IBM Data Science Professional Course`. The capstone project requirements are listed [here](https://www.coursera.org/learn/applied-data-science-capstone/peer/60zST/capstone-project-the-battle-of-neighborhoods-week-1).

## Description of problem:
The intent of this project is for restaurant owners. As mentioned in this [article](https://www.entrepreneur.com/article/306018), the few challenges faced by restaurant owners is finding an appropriate theme, keeping up with the competition and finding the right suppliers.

## Description of the Dataset:
### I will be utilising:
1. `Foursquare` API to retrieve users tips on restaurants. I will be including the top words used for top comments for each cuisine, this will be useful especially for owners who are hoping to know what customers are looking for. Sentiment Analysis using [textblob](https://github.com/sloria/TextBlob) will be applied to determine the sentiment of each word. I will also be applying [Latent Dirichlet allocation](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation) (LSA) topic modelling techniques to capture definitive clusters.
2. `Geocoder` API to retrieve the latitudes and longitudes of nearby restaurants and groceries. The number of restaurants around the vicinity of 500 metres will be used as a factor of consideration due to competition. The number of groceries nearby would be a useful gauge on the potential suppliers of the area.
