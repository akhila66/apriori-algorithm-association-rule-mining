# apriori-algorithm-association-rule-mining
apriori algorithm association rule mining implementation 


We can see the difference. As we increase support frequency no of False + and False – are decreasing. Since accuracy is increasing. 


Note that the analysis is not only to report the results you obtained, but also, very importantly, to explain why you get such results (e.g. “The Simple Randomized algorithm takes longer when the sample size increases” or “Apriori requires 15% more time than the Simple Randomized algorithm does” is not a complete analysis; you need to explain why these occur, which requires you to have a deep understanding of how the two algorithms work). See the reference list at the end of this homework assignment for a reference on the Simple Randomized algorithm. 


http://web.cse.ohio-state.edu/dmrl/papers/ride97.pdf (Reference Paper)

As we can see for all support frequency and for different sampled data it is taking almost same execution time. And we can also say that it is taking less time to execute as we take less probability of data. If we are getting same approximate rules with more accuracy it’s preferred to take sampled data instead of full 100 % data. This can help to improve out algorithm performance without losing any accuracy.



We have presented experimental evaluation of sampling for three different sample datasets and also with full data to show that it can be an effective tool for data mining. The experimental results indicate that sampling can result in not only performance savings (such as reduced I/O cost and total computation), but also good accuracy (with high confidence) in practice. However, we note that there is a trade-off between the performance of the algorithm and the desired accuracy or confidence of the sample. With that we can claim that for practical purposes we can use sampling with high confidence for any data mining tasks which has huge datasets. 
If data is having very limited transactions obviously it’s always better to go for full data (without sampling).  And if the data having huge no of transactions and after checking that trade-off b/w the performance and accuracy, depending of accuracy error we can choose if it satisfies our need.
