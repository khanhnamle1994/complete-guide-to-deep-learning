Probabilistic graphical models (“PGMs”) form a separate subfield at the intersection of statistics and machine learning. There are many books and courses on PGMs in general. Here we present how these models are applied in the context of deep learning. Hugo Larochelle's course describes a few famous models, while the book Deep Learning devotes four chapters (16-19) to the theory and describes more than a dozen models in the last chapter. These topics require a lot of mathematics.

* [3. Conditional Random Fields](https://www.youtube.com/watch?v=GF3iSJkgPbA&list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH&index=18)
* [4. Training CRFs](https://www.youtube.com/watch?v=6dpGB60Q1Ts&list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH&index=28)
* [5. Restricted Boltzman machine](https://www.youtube.com/watch?v=p4Vh_zMw-HQ&list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH&index=36)
* [7.7-7.9. Deep Belief Networks](https://www.youtube.com/watch?v=vkb6AWYXZ5I&list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH&index=57)
* [9.10. Convolutional RBM](https://www.youtube.com/watch?v=y0SISi_T6s8&list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH&index=78)
* [13. Linear Factor Models](https://github.com/khanhnamle1994/complete-guide-to-deep-learning/blob/master/Probabilistic-Graphical-Models/linear_factor_models.pdf) - first steps towards probabilistic models
* [16. Structured Probabilistic Models for Deep Learning](https://github.com/khanhnamle1994/complete-guide-to-deep-learning/blob/master/Probabilistic-Graphical-Models/structured-probabilistic-models-for-deep-learning.pdf)
* [17. Monte Carlo Methods](https://github.com/khanhnamle1994/complete-guide-to-deep-learning/blob/master/Probabilistic-Graphical-Models/monte-carlo-methods.pdf)
* [18. Confronting the Partition Function](https://github.com/khanhnamle1994/complete-guide-to-deep-learning/blob/master/Probabilistic-Graphical-Models/confronting-partition-function.pdf)
* [19. Approximate Inference](https://github.com/khanhnamle1994/complete-guide-to-deep-learning/blob/master/Probabilistic-Graphical-Models/approximate-inference.pdf)
* [20. Deep Generative Model](https://github.com/khanhnamle1994/complete-guide-to-deep-learning/blob/master/Probabilistic-Graphical-Models/deep-generative-models.pdf) - includes Boltzmann machines (RBM, DBN, ...), variational autoencoders, generative adversarial networks, autoregressive models etc.
* [Generative models](https://blog.openai.com/generative-models/) - a blog post on variational autoencoders, generative adversarial networks and their improvements by OpenAI.
* [The Neural Network Zoo](http://www.asimovinstitute.org/neural-network-zoo/) attempts to organize lots of architectures using a single scheme.

Higher level frameworks (Lasagne, Keras) do not implement graphical models. But there is a lot of code for Theano, Tensorflow and Torch.

* [Restricted Boltzmann Machines in Theano](http://deeplearning.net/tutorial/rbm.html)
* [Deep Belief Networks in Theano](http://deeplearning.net/tutorial/DBN.html)
* [Generating Large Images from Latent Vectors](http://blog.otoro.net/2016/04/01/generating-large-images-from-latent-vectors/) - uses a combination of variational autoencoders and generative adversarial networks.
* [Image Completion with Deep Learning in TensorFlow](https://bamos.github.io/2016/08/09/deep-completion/) - another application of generative adversarial networks.
* [Generating Faces with Torch](http://torch.ch/blog/2015/11/13/gan.html) - Torch implementation of Generative Adversarial Networks
