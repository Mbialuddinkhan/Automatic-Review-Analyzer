# Automatic-Review-Analyzer
The purpose of this project is to create a classifier that can be used to analyze sentiment in product reviews. The training set includes of Amazon user reviews for a variety of food products. The reviews, which were formerly offered on a 5-point scale, have been changed to a +1 or -1 scale, reflecting a favorable or bad rating.
To assess reviews automatically, we will need to complete the following tasks:

Three forms of linear classifiers are implemented and compared: the perceptron method, the average perceptron algorithm, and the Pegasos algorithm.

we can use some simple text characteristics to train classifiers on the meal review dataset.

Experiment with different features to see how they affect classifier performance.

Details of the setup:

We'll be using Python 3.6 with some additional libraries for this project. It is strongly advised to read through the NumPy tutorial and take notice of how the NumPy numerical library is used in the code provided. When it comes to numerical computation, NumPy arrays are far more efficient than Python's native arrays. Using NumPy will also save time.

Note on software: it needs the NumPy numerical toolbox and the matplotlib charting toolbox for this project.

The sentiment analysis folder contains the following python files: project1.py provides numerous important functions and function templates that will be used for analyses 

We will use project1.py to implement learning algorithms because it has a number of handy functions and function templates.

main.py is a skeleton script that calls these functions and allows to conduct experiments.

utils.py is a Python file that contains utility functions.

test.py is a Python script that tests a handful of the functions which are used. Please keep in mind that these tests are offered to aid in the debugging of implementation
