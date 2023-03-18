This folder include an implantation of K-means algorithm and two simulations to get a better understanding of statistical rules.
## K-means
K-means is an unsupervised algorithm(means we dont have label for data) which tries to find k point such that each point represent a cluster and we also aim to reduce intra cluster distance and increase inter cluster distance. 
in this part i trained this model on [iris](https://archive.ics.uci.edu/ml/datasets/iris) for differnet numbers of K in 150 epochs to see the effect and it was clear that as we increase K the intra cluster to inter cluster distance ratio became smaller and 20 was the best value for k. also i repeated training for 100 times and beacause of random initialization of centroids to points in dataset it converged to same answer each time.

## Statistical simulations
in this section i first did the famous birthday problem simulation. in this simulation we want to the probablity of two people having the same birthday in crowd with n individual and the resaults indicated that with n=60 we almost certainly have two people with same birthday.

after that i generated 2000 samples with size = 100 from  exponential and binomial distributions. mean of this smaples as we expect was converging to original distribution and variance of means became very close to 0 as a resault of big number of sample size.
