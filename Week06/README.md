## A basic application of Deep Convolutional Generative Adversarial Network (DCGAN)

- primary aim was to train a DCGAN on the Fashion-MNIST dataset
- secondary aim was to provide a few test inferences

## Test Inference from the trained DCGAN model after `3000` epochs

![](https://github.com/Dexter1618/MMWML/blob/master/Week06/after_3000_epochs.png)

## Notebook

You can find the notebook rendered on Jupyter nbviewer [here](https://nbviewer.jupyter.org/github/Dexter1618/MMWML/blob/master/Week06/GAN_FashionMNIST.ipynb).

## Introducing the Fashion-MNIST

[Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist) is a dataset of [Zalando's](https://jobs.zalando.com/en/) article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. We intend Fashion-MNIST to serve as a direct drop-in replacement for the [original MNIST dataset](http://yann.lecun.com/exdb/mnist/) for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

<img src = "https://tensorflow.org/images/fashion-mnist-sprite.png" width = 450 height = 400>

## Why was the Fashion-MNIST created?

The original MNIST dataset contains a lot of handwritten digits. Members of the AI/ML/Data Science community love this dataset and use it as a benchmark to validate their algorithms. In fact, MNIST is often the first dataset researchers try. _"If it doesn't work on MNIST, it won't work at all"_ , they said. 

_"Well, if it does work on MNIST, it may still fail on others."_

<img src = "https://github.com/zalandoresearch/fashion-mnist/raw/master/doc/img/embedding.gif">

<br>

Here are some good reasons to replace MNIST:

- __MNIST is too easy__: Convolutional nets can achieve 99.7% on MNIST. Classic machine learning algorithms can also achieve 97% easily.
- __MNIST is overused__: In [this April 2017 Twitter thread](https://twitter.com/goodfellow_ian/status/852591106655043584), Google Brain research scientist and deep learning expert Ian Goodfellow calls for people to move away from MNIST.
- __MNIST can not represent modern CV tasks__, as noted in [this April 2017 Twitter thread](https://twitter.com/fchollet/status/852594987527045120), deep learning expert/Keras author François Chollet.

## References

- Rowel Atienza's [book](https://www.amazon.com/Advanced-Deep-Learning-Keras-reinforcement/dp/1788629418/) and [Medium article](https://towardsdatascience.com/gan-by-example-using-keras-on-tensorflow-backend-1a6d515a60d0) provided my fundamental understanding of implementation of a simple Deep Convolutional GAN (DC-GAN)
- Rowel also attached a sample python [script](https://github.com/roatienza/Deep-Learning-Experiments/blob/master/Experiments/Tensorflow/GAN/dcgan_mnist.py) in the Medium article referenced above which had a template of the code
- Github User `R-Suresh`'s [code](https://github.com/R-Suresh/GAN_fashion_MNIST/blob/master/gan.py)
