# Airbnb_MachineLearning

The purpose of the project was to use Frequent Pattern Mining algorithm to find associations between items in the dataset. 
<br>
Our data was downloaded from Kaggle and was in csv format. The Airbnb dataset has 25,458 rows and 213 columns.
<br><br>
We used different algorithms within Frequent Pattern Mining like Apriori, Association Rules, and Frequent-Pattern Growth, from different packages like ML-Xtend and Spark packages. The model identified the itemsets that are regular/popular amongst the Airbnb dataset.
<br><br>
Number of reviews an Airbnb has does not significantly impact its review score rating and therefore does not have much effect on the predicted itemsets. There seems to be a basic set of amenities that are provided by all Airbnb - {wireless internet, heating, kitchen, and essentials}. If an Airbnb host wants to increase his/her review scores, additional amenities need to be provided either individually or in a bundle. In addition to the basic sets of amenities. In our analysis we found that those Airbnb with high number of reviews and high review score rating provided additional amenities like hair dryer, iron, and laptop friendly workspace. In future analysis, we would need to include more information to better predict the set of items that correlate with high review scores. For example, we could factor in the quality of the neighborhood, the type of stay (business trips or vacation).
