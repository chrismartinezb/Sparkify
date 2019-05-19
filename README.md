# Sparkify

Predicting churn is an everyday problem in data science. It is quite important for companies to identify customers who are likely churn and try to retain them before they do. The goal of this project is to help Sparkify identify such customers.
Such a prediction can be made for each customer by a binary classifier model. 
We will follow the next steps in order to achieve such a prediction:

- Analyze the data to identify the key features to feed to an ML algorithm.
- Create such features.
- Try different algorithms and pick the best based on a chosen metric.
- Train and tune the algorithm.
- Plot the most important features of the algorithm.
- Such finding will give us a deeper insight into our customers and their behavior as well as a robust model to predict new possible churn customer.

 Check this [blogpost](https://medium.com/@chris.martinez.bernal/sparkify-713da6c16bd3) for a deeper insight on the project.

# Install

This project requires **Python 3.6** and the following Python libraries installed:

- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org)
- [Pyspark](http://scikit-learn.org/stable/)
- [Seaborn](https://www.nltk.org/install.html)
- [Matplotlib](https://xgboost.readthedocs.io/en/latest/)


## Data

The [dataset](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/December/5c1d6681_medium-sparkify-event-data/medium-sparkify-event-data.json) consist in 543705 entries of user's datalogs. They contain information such as  user name, gender, location,ong listened, event type, device used,etc.
 
 ## Process

- Loading the data.

- Cleaning the data.

- Exploring the data.

- Feature Engeneering.

- Model testing.

- Model Tuning

- Most importan features.


## File description.

[Notebook](https://github.com/chrismartinezb/Disaster_response_pipeline/tree/master/app): You can follow the step by step on this notebook.
 
## Conclusions.

- How much time the user spent on the app was a key feature when predicting churn, which is obviously correlated with other interactive features like thumbs up and down, getting the users to spend more time on the app is key to prevent churn, creating a more interactive experience than just listening to music and adding new interaction with music sure will help.

- Sparkify has a high churn rate and should be a priority to stop it. 

- The level of the user was not really important when churning, even if our user pays the subscription is not a guarantee that he will stay.

## Licensing, Authors, Acknowledgements

- To [Udacity](https://www.udacity.com/) for providing the starter code as part of their Data Sciencde Nanodegree program.

For the remaining code, feel free to use it as you wish.
