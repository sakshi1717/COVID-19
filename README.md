# COVID-19

# Inspiration
The increasing threat that COVID-19 poses to everyone around the world inspired me to come up with a solution to mitigate the repercussion of the deadly virus. It has been closely noted that during these times of lockdown there has been a rise in the crime rate throughout the length and breadth of our country . Farmers or daily wage workers barely have money to make their end meet therefore the snatching and thievery cases are rising sharply . Also not to forget that since we all are locked up in our homes 
for quite a long time the cases of domestic violence have been seen rising .

According to TIMES OF INDIA
“Domestic violence has often been studied as an abusive expression triggered by financial stress, mental stress, fear, and of course, systemic patriarchy, that has furthered the cases of financial abuses, and at times, even murders. The national lockdown has reported more than 50% rise in domestic violence”. Therefore this is the right time to take necessary action and save India from the Domestic Violence Pandemic

# What it does
It is a very simple model and we have trained the model using machine learning techniques. It predicts the crime rate in the new communities. This model takes into account 95 features such as the number of homeless people, income , family size, percentage of children that graduate high school, size of police force, employment status , etc and then it outputs the probability of the crime rate in that particular area.


# How we built it
We used the regularization technique to predict the crime rate in a particular house/ locality / community . Then we calculated the squared error on the training and test data and adjusted the value of lambda . To avoid overfitting problem ,we used the descent LASSO algorithm for this model. LASSO is a regression analysis method that performs both variable selection and regularization in order to enhance the prediction accuracy and interpretability of the statistical model it produces.

# Observation :
★ The lambda that gave the best test set performance is 18.
★ The variable that had the largest Lasso coefficient is NumStreet.
★ The most negative one is PctFam2Par.This makes sense where the place that
has the most homeless people counted in the street will likely have more crimes.
★ The family with kids that are headed by two parents seem educated, this will be
likely to have less crimes.

The dataset has been taken from
(http://archive.ics.uci.edu/ml/machine-learning-databases/communities/communities.names)
