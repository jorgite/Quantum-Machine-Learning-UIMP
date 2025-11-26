Obtained from tutorials / practical lecture...
Try to implement them or at least take them into account in the solution of the exercise


Some ideas of other master students:
    --> For Hoeffding and Chebyshev and for each distribution I have plotted the confidence interval Epsilon vs the probability P of being inside that range (with P from 0 to 1). So 2 curves per distribution.
    --> I just presented the values and then I have estimated how many times the mean is in the intervals estimated
    --> The plot i have done is to compare the width between intervals estimated with chebyshev hoeffding and with the central limit theorem

General knowledge
    --> We can almost always normalize our variable to keep it between 0 and 1 (we won't do it but we could)
    --> the P1-P3 is about comptuing error bars / confidence intervals
    --> we have to suppose that the random data we generate is given to us via an experiment (this implies that we don't know the ideal distribution used to generate the random data, so either the real mean and variance)
    --> with that data we can compute it's average and we want to give and error bar to this number (an interval of which we can be sure that the mean of the real ideal distribution is inside with a certain confidence level)
    --> something to try should be playing with the number of elements generated (it will get worse if we use a smaller number of data)
    --> for P1 it'd be interesting to study and understanding the scalability of the parameters (video of the class, 1h25min aprox)

Hoeffding inequalities / bounds
    --> We have some random variables (independent) bounded in an interval (it can be different for each of them)
    --> the smallest the interval for each variable, the better (it will provide a narrower interval for the mean given level of confidence)
    --> it's always useful but not always very tight

Chebishev inequalities / bounds
    --> in practice it only works with some distributions, because we are suppossed to know the real variance of it (not the one that we can calculate given the data)
    --> works well (better than Hoeffding) if the variance is know and small
    --> in fact, it gives an interval of confidence for EACH variable (refered to the real mean)
    --> if we want a 95% confidence, then we have to get the epsilon to get that confidence and that defines our error bar

68-95-99.7
    --> https://en.wikipedia.org/wiki/68%E2%80%9395%E2%80%9399.7_rule
    --> in principle it should work only in the gaussian distribution, not in the other cases. to do so compare with the resoults of P1