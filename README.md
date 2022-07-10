# Binary Node Classification for Twitch Social Networks Data


# Abstract

In this study, the user-to-user Twitch network is held as a network analysis topic. The dataset
consists of six different countries as six separate network structures. Spain (ES) network is
selected for the analysis to overcome the computation problems. Community detection may
be important for social network analysis to discover communities and get insides from the
network. Therefore, for the community detection of Twitch dataset, two different approaches
have been applied. Firstly, the Louvain method is used and 6 communities were found.
Secondly, the Girvan-Newman method was applied. The Louvain method yielded a better
modularity result for the community detection of the network. For the binary node classification
task, 3 different feature datasets were utilized. Firstly, node embedding vectors were calculated
and features extracted from node2vec approach were used as predictor for the prediction task.
Thirdly, Rolx algorithm was applied and extracted features were used for the prediction task. Finally,
node2vec and Rolx features were combined with the own properties of Twitch network data and
this merged features were used for the prediction task. In the binary node classification
problem, the Logistic Regression and Random Forest Classifier algorithms were used. The best
model was obtained with the node2vec features and Random Forest algorithm with 96% F1
score.
