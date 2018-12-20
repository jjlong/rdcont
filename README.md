# rdcont
A common practice in the regression discontinuity design (RDD) is to test the hypothesis that the running variable has a continuous density at the threshold. -rdcont- tests this hypothesis using an approximate sign test, as detailed in Bugni and Canay (2019). Relative to competing tests, the approximate sign test is asymptotically valid under mild conditions. The rdcont test is implemented by default using the data-dependent choice of “q” provided by Bugni and Canay (2019).