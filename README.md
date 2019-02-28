#Sports Analytics Hackathon

Special note-

1-For ODI series prediction there is not enough data to predict who is the winning team because austrailia has not visited to play in india's field much.

2-India and Australia has played 7 times where india won 4 and Asutralia won 2, and these data has been taken after 2010.

3-After compilation of these data india's win prediction 57% and australia win chances is 28%.

4-Many of the players are debuted and new to play this series against each other so there is no specific data which will affect the win or loose of any team.



After ODI series prediction data has taken from Cricbuzz source where each player's data has taken against overall team not against just 
Australia to avaoid biasing of the dataset.

DATA SELECTION

1-rediff cricket & cricbuzz are the main sources from where data is collected for further analysis and predictions.

2-The data present over here in a proper manner between australia and india all matches played.

3-we have also taken the data overall against every team so we can avoide biasing.

4-also we have seen many of the players are debut in ODI series so there is no source of previous data, we have taken 0 rather than taking NA values.



DATA CLEANING

Got nan values in data set,which i modelled via replacing that value with 0.
the data type of variable is changed whereever necessary from float to INT type.

DATA MODELLING

i have used K-Means algorithm along with herarichal clustering algorithm cause clustering was required to predict the winning team and its data sets.

DATA VISUALIZATION

Barplot is used here to visualize the data because we have to show the cluster response i.e. which clusters is going to perform well or not on the basis of variables behaviour.


EVALUATION

The result was evaluated on the basis of cluster behaviour and their response.
for take a case :->
HOW TO PREDICT TOP SCORER BATSMEN
1.past data is collected from cricbuzz source site.

2.the main column to make conclusion was average and strike rate.

3.the clusters formed are basis on these two variable behaviour.

