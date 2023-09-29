# Liver_Disease_Prediction
Spearheaded research tackling the paramount global issue of Liver Disease, impacting populations worldwide. Employed intricate machine learning techniques to decipher complex patterns within vast datasets, enabling insightful decision-making.

Utilized the Indian Liver Patient Dataset (ILPD) from the University of California, Irvine repository to conduct a comprehensive analysis. Leveraged key health indicators like Alkaline Phosphatase, Alamine Aminotransferase, and others to predict future health scenarios.

Employed advanced machine learning algorithms such as Logistic Regression, Random Forest, and Naive Bayes for accurate predictions.

Orchestrated the creation of an intuitive Flask interface, enabling users to determine their liver health status confidently. Selected the most accurate machine learning algorithm to determine outcomes.

Steps for Execution:

First import all the necessary python libraries.

Perform data pre-processing and exploratory data analysis, to eliminate the duplicate values. 

In exploratory data analysis the plot used are scatter, countplot, histogram, box plot, joint plot, facetgrid, pairplot etc..

Calculate correlation of each column in the data frame. Draw the correlation matrix

The algorithms used are:
Logistic Regression, K Nearest Neighbor, Support Vector Machine, Random Forest Classifier, Naive Bayes Classifier.

After coding and selecting the best model import it in the flask code and keep them all in same directories.

Now for the final result we need to open our Anaconda prompt and run the flask code. 

Once the flask code is executed in the command prompt exclusively with admin access, you will be greeted with webpage link which will take you to the output of the project where initially an index page is shown.

The user enters the values for the attributes shown on the web page and clicks on the 'Submit' button. 

The predicition is shown whether the user has Liver Disease or not.
