# CS231n Assignment3
This repository contains the solutions for the third Programming Assignment from **CS231n: Convolutional Neural Networks for Visual Recognition.** Implemented the following:

- Image captioning models

   Given an input image, this model generates a caption describing the image in English. Generated text using Vanilla RNN's and LSTM's.

- Image saliency maps

   Finds out the regions in an input image that influenced the network's decision for a particular image and a class. 

- Generated fooling images

   Modified an input image mildly using optimization techniques to fool the network. Even though the changes were imperceptible, the network misclassified the new image with a high confidence.

- Google DeepDream

   Generated trippy images by tweaking the image iteratively for boosting the activations of a particular layer in the network. This work done originally by Google is explained in detail in their [blog post](https://research.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html).
