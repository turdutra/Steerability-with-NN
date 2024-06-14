# Steerability-with-NN
This project implements and compares there neural networks to detect steerability on a two-qubit state. The content folder contains the necessary auxilary files. 

To train the network we use a state detabase from https://github.com/BiduRuiz/SDP_LocalModels.

The LHS certification.ipynb program is a julia program takes that database and implements an algorithim developed by https://arxiv.org/abs/1808.09349 to determine which are steerable. 

The ML_code.ipynb colab notebook takes the output from the previous code and defines and trains the networks
