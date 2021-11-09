# Statistics for machine learning

## Calculate confidence intervals and compare classifier performance using delong test and bootstraping

The code for bootstraping is based on
https://machinelearningmastery.com/calculate-bootstrap-confidence-intervals-machine-learning-results-python/ https://stackoverflow.com/questions/19124239/scikit-learn-roc-curve-with-confidence-intervals
Here I assume that the distribution is normal and the samples are independent. In the original vairant, they calculate empirical CI (non parametric) without assuming a normal distribution

The code for delong test is taken as is from:
https://github.com/yandexdataschool/roc_comparison
