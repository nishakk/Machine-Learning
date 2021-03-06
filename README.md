# Machine-Learning

Machine Learning Algorithms implementations from scratch

## Decision Tree Learning Algorithm and Prediction
Data is assumed to contain attributes with binary values and the output is also binary. Mutual Information is used as the splitting criteria. The attribute with highest mutual information value is used as the node to split the data. Mutual information less than 0 are not considered. The node becomes the terminal node for making decision.

## Logistic Regression
Logistic Regression algorithm (lr.py) used with feature engineering (feature.py). feature.py modifies the movie review (data) to a sparse representation using the dictionary provided. lr.py performs binary logistic regression on the formatted data and predicts positive or negative review for the test data. 

## Neural Network

Neural Network (with single hidden layer) implementation from scratch. Output size is assumed to be 10 (Implementation supports any number of output).

## Hidden Markov Model

Implemented HMM using Forward Backward Algorithm. learnhmm.py implements HMM parameters needed for estimation: initialization probabilities, transition probabilities and emission probabilities. forwardbackward.py implements Forward Backward Algorithm by recursively passing through "forward" and "backward" components. Finally the tags are assigned (labeling) using Minimum Bayes Predictor. Log-likelihood is calculated for each sequence and averaged out to get the overall log-likelihood of the data.

## Reinforcement Learning: Q-Learning

Implemented Q-learning on Mountain Car environment, with epsilon-greedy action selection to select the optimal action. To simplify the implementation, two modes are considered: raw, which is the discretization of the state space of Mountain Car, and tile, which is coarse-coding of the state space.
