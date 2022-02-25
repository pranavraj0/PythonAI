Tweet Classifier Multi-Layer Perceptron:

To classify our Tweets, we'll be using a Multi-Layer Perceptron, or MLP for short. Despite the fancy-sounding name, it's one of the oldest and simplest kinds of neural networks used in machine learning. Due to their versatility, they are often used in some form in many neural networks.

We'll train our MLP to map the 768-dimensional vectors (which are stored as `torch.Tensor` objects) into a vector of length 20, which represents the probability of each possibility. 

If you run all the cells, you will get a prediction for the arbitrary tweets at the end (accuracy may not be too good, though)
