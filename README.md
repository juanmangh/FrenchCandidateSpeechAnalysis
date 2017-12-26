# FrenchCandidateSpeechAnalysis
In this project, speeches of the French candidates are analyzed with the intention of discovering if their opinions are similar. To do so, speeches are broken down to sentences, they are represented using word2vec and then a Convolutional Neural Network is trained. In the last layer of the neural network, each neuron is associated to one candidate. When one sentence is passed as input, each neuron of the last layer will have a value that will represent how much that sentence is related to the candidate. The values of the last layer neurons add up to 1, so it can be interpreted as a percentage.

The project is based on the following paper: https://arxiv.org/pdf/1408.5882.pdf
