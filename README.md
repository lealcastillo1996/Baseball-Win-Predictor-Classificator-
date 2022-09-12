
The **objective** of this project is to create an accurate as possible machine learning classification model for determining whether or not a baseball team is going to win a game as local.

![alt text](https://imageio.forbes.com/specials-images/imageserve/60502c89850eaa01f8e5d84a/Boston-Red-Sox-v-Tampa-Bay-Rays/960x0.jpg?format=jpg&width=960)

## Overview
### - Initial EDA:
A dataset gathered from a famous sports website will be used to gain initial insights for this project.

- Missing values handling
- Temporal relationship
- Numerical variables distribution
- Categorical variables
- Dependent variable relantionships
- Correlations
- Conclusions from data

### - Data transformation:

In this step, new features summarizing previous games performance will be generated


### - Advanced EDA:
In this step, a new analysis using the generated variables in the step will be performed

The features created now correlate better than original ones, however the correlation keeps weak. A model of classification will be constructed with this features as intances, we will try to choose a not flexible model  (linear model) because correlation is not strong enough, therefore variance is big and we dont want to fall in an overfit problem


### - Feature Engineering:

In this step, the created dataset will be cleaned. Secondly a a train and test set will be generated.  Finally the sets numerical variables will be normalized using a standard deviation scaler.

Two scaled sets were generated and are ready to apply machine learning models on them (Train set: 8479rows, Test set: 2120 rows) 

### - Naive-Bayes Classificator

Naive- Bayes classicator algorithm was choosed because is among one of the best unflexible classificators when large variance is observed in data.



### - Results summary

Even though the predictors didnt correlate so well with the output, a classificator with a reasonable accuracy was possible to create, especially for the True predictions of a Local Team to win. (63%)


Application of  this classificator for sport betting should be analyzed since the game odds  of sportbooks are  so tricky and maybe a revenue with this accuracy could no be  possible without a correct betting strategy.

![alt text](https://media.discordapp.net/attachments/929043644512624691/1018974875693625414/Captura_de_Pantalla_2022-09-12_a_las_21.59.53.png)
