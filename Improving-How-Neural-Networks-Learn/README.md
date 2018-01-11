It's not very easy to train neural networks. Sometimes they don't learn at all (underfitting), sometimes they learn exactly what you give them and their "knowledge" does not generalize to new, unseen data (overfitting). There are many ways to handle these problems.

* [2.8-2.11. Regularization, parameter initialization etc.](https://www.youtube.com/watch?v=JfkbyODyujw&list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH&index=14)
* [7.5. Dropout](https://www.youtube.com/watch?v=UcKPdAM8cnI&list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH&index=55)
* [6 (first half). Setting up the data and loss](https://www.youtube.com/watch?v=KaR4lIdI1MQ&list=PLlJy-eBtNFt6EuMxFYRiNRS07MCWN5UIA&index=6)
* [3. Improving the way neural networks learn](http://neuralnetworksanddeeplearning.com/chap3.html)
* [5. Why are deep neural networks hard to train?](http://neuralnetworksanddeeplearning.com/chap5.html)
* [7. Regularization for deep learning](https://github.com/khanhnamle1994/complete-guide-to-deep-learning/blob/master/Improving-How-Neural-Networks-Learn/Regularization_for_DL.pdf)
* [8. Optimization for training deep models](https://github.com/khanhnamle1994/complete-guide-to-deep-learning/blob/master/Improving-How-Neural-Networks-Learn/Optimization_for_Training_Deep_Models.pdf)
* [11. Practical methodology](https://github.com/khanhnamle1994/complete-guide-to-deep-learning/blob/master/Improving-How-Neural-Networks-Learn/Practical_Methodology.pdf)
* [ConvNetJS Trainer demo on MNIST](http://cs.stanford.edu/people/karpathy/convnetjs/demo/trainers.html) - visualizes the performance of different optimization algorithms
* [An overview of gradient descent optimization algorithms](http://ruder.io/optimizing-gradient-descent/)
* [Neural Networks, Manifolds, and Topology](http://colah.github.io/posts/2014-03-NN-Manifolds-Topology/)

There are many frameworks that provide the standard algorithms and are optimised for good performance on modern hardware. Most of these frameworks have interfaces for Python with the notable exception of Torch, which requires Lua. Once you know how basic learning algorithms are implemented under the hood, it's time to choose a framework to build on.

* [Theano](http://deeplearning.net/software/theano/) provides low-level primitives for constructing all kinds of neural networks. It is maintained by a [machine learning group at University of Montreal](https://mila.quebec/en/).
* [TensorFlow](https://www.tensorflow.org/) is another low-level framework. Its architecture is similar to Theano. It is maintained by the Google Brain team.
* [Torch](http://torch.ch/) is a popular framework that uses Lua language. The main disadvantage is that Lua's community is not as large as Python's. Torch is mostly maintained by Facebook and Twitter.

There are also higher-level frameworks that run on top of these:

* [Lasagne](http://lasagne.readthedocs.io/en/latest/user/tutorial.html) is a higher level framework built on top of Theano. It provides simple functions to create large networks with few lines of code.
* [Keras](https://keras.io/) is a higher level framework that works on top of either Theano or TensorFlow.
