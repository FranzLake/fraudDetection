
This project contains two Notebook files (.ipynb), each of which contains an ML model to address the problem of Credit Card Fraud Detection. Both Notebooks are based on the Kaggle dataset "Credit Card Fraud Detection", which can be find in the next link: https://www.kaggle.com/mlg-ulb/creditcardfraud

The first notebook contains a Multivariate Gaussian Distribution model proposal, which means the density estimation is calculated for all of the attributes simultaneously, taking them as a whole.

Unlike the first notebook, the second model contains a Univariate Gaussian Distribution model proposal, which means the density estimation is calculated individually for each of the attributes and, then, a general probability is calculated by taking the product of the set of distribution.

In order to correctly classify the maximum number of samples, without biasing the results to one of the classes, a threshold is established. The first option to calculate such a threshold was to employ the F1 Score, however,the classical F1 score results in very poor results due to highly unbalanced classes. Instead, a measure which considers the accuracy of both classes is proposed.

For reasons of time, I have't been able to publish a complete explanation of both models. I hope this little text, along with the notes in the .ipynb files are enough to understand the project. 