# Quora Insincere Questions Classification
Notebook for the Quora Insincere Questions Classification challenge on Kaggle.
Landed me in top 22% on the public LB and top 62% on private LB (most of the teams did not get their submissions tested on the private LB).

Uses a mixture of several neural networks. The blending weights were obtained using a 90-10% CV split (stratified), and using the 10% validation set to train a simple linear regression on the predictions. The submission was re-run with the fixed weights and using the full train set for training. Same approach was used for the F1 threshold computation.
Number of epochs for training was chosen manually looking at validation set F1-score.
