Obtained from tutorials / practical lecture...
Try to implement them or at least take them into account in the solution of the exercise
Delete it since I include it into the solution

Some ideas of other master students:
    --> For Hoeffding and Chebyshev and for each distribution I have plotted the confidence interval Epsilon vs the probability P of being inside that range (with P from 0 to 1). So 2 curves per distribution.
    --> I just presented the values and then I have estimated how many times the mean is in the intervals estimated
    --> The plot i have done is to compare the width between intervals estimated with chebyshev hoeffding and with the central limit theorem

General knowledge
    --> We can almost always normalize our variable to keep it between 0 and 1 (we won't do it but we could)
    --> something to try should be playing with the number of elements generated (it will get worse if we use a smaller number of data)
    --> for P1 it'd be interesting to study and understanding the scalability of the parameters (video of the class, 1h25min aprox)

Hoeffding inequalities / bounds
    --> the smallest the interval for each variable, the better (it will provide a narrower interval for the mean given level of confidence)
    --> it's always useful but not always very tight

Chebishev inequalities / bounds
    --> works well (better than Hoeffding) if the variance is know and small
    --> in fact, it gives an interval of confidence for EACH variable (refered to the real mean)
    --> if we want a 95% confidence, then we have to get the epsilon to get that confidence and that defines our error bar

68-95-99.7
    --> https://en.wikipedia.org/wiki/68%E2%80%9395%E2%80%9399.7_rule
    --> in principle it should work only in the gaussian distribution, not in the other cases. to do so compare with the resoults of P1






----------------------------------------------------------------------------------------------------------------------------------
SOME DOUBTS WHILE DOING THE EXERCISE

PROBLEM 0

1. The distributions we are doing are continuous or discrete? see Uniform in the case of a=0 b=1 to understand why i'm worried
2. The beta distribution is not normalized??!?!?!??!!?
3. maybe in problem 0 is needed more word type comparation

-------

PROBLEM 1-3

