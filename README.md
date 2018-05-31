# EXEPeek

For training neural-network, we have awesome back-propagation algorithm in order to automatically tweak our weights and biases to fit the dataset. This is just a project came out of curiosity for another method that is possible to tweak the network without depending on any model-based algorithm.

To be honest, back-propagation is still the winning choice here. This is just a proof-of-code project, which proved that randomness of genetic algorithm still possible to let the network learn, albeit very slow learning.

Noted, for large dimension of data (mnist/cifar-10) datasets, back-progapation wins the competition by tenfolds. That is why for this project I chose to use Iris dataset, as it dataset is small enough for me to conduct an experiment.