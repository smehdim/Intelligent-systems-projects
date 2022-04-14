
## decision tree and random forrest

aim here for decision tree and random forrest notebooks is to train a model to predict (Recidivism - Return to Prison numeric) as accurate as possible.our approach is to first train decision trees and then using written class for decision tree(named node) we can impelent random forrest. used criteria to optimize tree is cross entropy which means we aim to decrease entropy as much as we can.

first i defined claculate entropy and then used it in next function wich will take one column and corresponding label and returns entropy on that column given label column.then i will use this function in node class to calculate entropy for different splits and will choose best of them. at last using multiple trees and training them with different random columns and rows our random forrest classifier is ready too. resaults and measures of models are available for different tree depths. due to unbalanced depency on different columns random forrest performance will not be much different than decision tree.


## k neighbors and metric learning
k means is a clustering algorithm to cluster non labeled data.one of ideas to make it work better is metric learning which will transform data given some specific criteria for each metric learning method. to choose proper k for k_means its usual to run algorithm with different k values and compare the performances.
