### Supervised Learning
The word supervised comes from a word called supervisor i.e a person who helps and direct others.
In Machine Learning, Supervised Learning refers to a technique where we `train` or `teach` machine based on a `labelled data`.
Labelled Data means some data are tagged with their correct answer.
The majority of practical machine learning uses supervised learning.

Supervised learning is where you have `input variables (x)` and an `output variable (Y)` and you use an algorithm to learn the mapping function
from the input to the output.

                                                          Y = f(X)

The goal is to approximate the mapping function so well that when you have `new` input data (x) that you can predict the output variables (Y) for that data.

Supervised learning problems can be further grouped into `Regression` and `Classification` problems.

* Classification: A classification problem is when the output variable is a category, such as “red” or “blue” or “disease” and “no disease”.
* Regression: A regression problem is when the output variable is a real value, such as “dollars” or “weight”.

### Unsupervised learning
Unsupervised learning is the training of machine using information that is `neither classified`
`nor labeled` and allowing the algorithm to act on that information without guidance. 
Here the task of machine is to group unsorted information according to `similarities`,
`patterns` and `differences` without any prior training of data.
Unsupervised learning is where you only have input data (X) and `no` corresponding output variables.
Unlike supervised learning, no teacher is provided that means no training will be given to the machine. 
Therefore machine is restricted to find the hidden structure in unlabeled data by our-self.

Unsupervised learning classified into Clustering and  Association:

* Clustering: A clustering problem is where you want to discover the inherent groupings in the data, 
such as grouping customers by purchasing behavior.
* Association: An association rule learning problem is where you want to discover rules that describe large portions of your data, 
such as people that buy X also tend to buy Y.

### Semi-Supervised Machine Learning

Problems where you have a large amount of input data (X) and only some of the data is labeled (Y) are called semi-supervised learning problems.
These problems sit in between both supervised and unsupervised learning.
Many real world machine learning problems fall into this area
