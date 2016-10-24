# platt

This is a python implementation of Platt's normalization of classifier output scores to a probability value. It is an implementation of the Algorithm presented in:
Platt, John C. “Probabilistic Outputs for Support Vector Machines and Comparisons to Regularized Likelihood Methods.” In Advances in Large Margin Classifiers, 61–74. MIT Press, 1999.
URL: http://citeseer.ist.psu.edu/viewdoc/summary?doi=10.1.1.41.1639

Often times, after training a classifier, the output scores of a classifier need to be mapped to a more interpretable value. Platt's normalization is a classical method of doing just that. It fits a sigmoidal function z = 1/(1+exp(A*v+B) to the output scores v from the classifier and targets. The coefficients of the sigmoidal function can then be used to transform the output of any output from the classifier to a pseudo-probability value.

Implemented by: Dr. Fayyaz Minhas, DCIS, PIEAS (http://faculty.pieas.edu.pk/fayyaz/)
