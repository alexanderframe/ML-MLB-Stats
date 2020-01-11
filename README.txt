Alex, Matt, Theresa, Josefina, Steven

We are interested in diving into a sports database to analyze and predict future trends in MLB.
Our dataset comes from Sean Lahman, a sportswriter that creates a database each year that includes most MLB historic statistics.
Link to dataset:
http://www.seanlahman.com/baseball-archive/statistics/

We used a keras logistic regression model to see if we could train a model to accurately predict if a team will make the postseason based on either their end of year or current statistics.

To get the necessary data for the keras model, we uploaded different csv files provided by Sean Lahman into a postgres database so that we could join together the specific tables we needed and export them to a singular csv that we used in our ML jupyter notebook.

We trained one model on those basic statistics that we got from the dataset.  We then used those base stats to create more advanced statistics that are normalized to the numbers of games player and trained a second model on those to allow the model to be used at any point in the season.

We will present this project by adding our new information gained from this project to a heroku deployed webpage that we created for project 2.
