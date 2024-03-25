# EECS3401FinalProject
## The Movie and Show Predictor
In this project, the goal is to predict what the general public might rate a movie or show on IMDB. Movies and shows were gathered from the Netflix streaming site and the ratings used to train the models were gathered from IMDB. All of this data can be found in the datasets folder.
The highest correlations were between the average IMDB rating of a movie or show was with the overall cumulative IMDB score average of all the filmmakers based on their other works. 
## Models Used
[*] Linear Regression
[*] Ridge Regression
[*] Lasso Regression
The best performing model was the Linear Regression model.
## Some EDAs Analyzed
Correlations between cumulative average filmmaker IMDB score and the IMDB score of specific Movie or Show 
![Screenshot 2024-03-24 224325](https://github.com/Vladboy2/EECS3401FinalProject/assets/77248716/5fc48789-b0ac-470f-8faf-d099124e3d05)
![Screenshot 2024-03-24 224417](https://github.com/Vladboy2/EECS3401FinalProject/assets/77248716/bc30eb53-99e6-4b78-9ad9-1ea135c3f1f3)

Scatter plot showing the Predicted Vs. Actual Values from the Linear Regression Model
![Screenshot 2024-03-24 224625](https://github.com/Vladboy2/EECS3401FinalProject/assets/77248716/c0f75657-6a3a-44af-a4df-43c463c59dfc)

Performance Comparion between the Three Models
![Screenshot 2024-03-24 224730](https://github.com/Vladboy2/EECS3401FinalProject/assets/77248716/6aee6b49-f1b5-4863-a690-f069bbb5667d)

## Conclusion
The models weren't able to determine a close enough rating to the actual rating of each respective movie or show in the testing set. This can be a number of things, such other variables and attributes not considered in training the models. With more research this can be corrected. Overall, this shows that movies and shows are still very much subjectif and no number of factors can predict what viewers might rate a movie or show to be.
