# Deep Neural Networks

## Abstract 

This project is the first project completed for Machine Learning and Data Mining course during my senior year at the University of Toronto. In this project, I explored the effectiveness of applying linear regression on classfications problems of two different actors, two different genders and the overfitting problems. I also visualized the final weights used on the feature vectors. 

## Acknowledgements

I would like to thank my collaborator, Yuan Yao, for his strong dedication and intelligence to make this project a great one.

## Problems 

The specific instructions of this project could be found in the [instructions link](http://www.cs.toronto.edu/~guerzhoy/411/proj2/). In this project, we used the classic MINST handwritten digits dataset and the facescrub dataset to explore the following aspects of deep neural networks

1. classify which class a handwritten digit belongs to using a single layer neural network, compare the results with the linear classifiers
2. classify which actor is in the image given a image data using two layer neural network
3. visualize the weights generated by the neural network of the features as images
4. build on the activation value of AlexNet, build a fully-connected neural network to classify the actors image

The [!FaceScrub](http://vintage.winklerbros.net/facescrub.html) Dataset is downloaded from UC Irvine machine learning repository. The original images looks like the following after preprocessing. 

[![Capture.png](https://s18.postimg.org/ok59iyp7d/Capture.png)](https://postimg.org/image/bsr3cgff9/)

The MINST dataset is directly read from the provided .mat file in this repository. The data looks like the following after preprocessiing.

[![Capture.png](https://s14.postimg.org/jbzbf3f29/Capture.png)](https://postimg.org/image/5iayq1mgt/)

The specific report of this project could be found in the [deepnn.py](./deepnn.py) file in this repository.

## Results

For the MINST dataset, the **superior performance of single layer neural network to linear classifier** is evident from the better performance in both the training set and the test set. 

The performance on training set using logistic method is : **86.25%**
The performance on test set using logistic method is : **83.3%**

The performance on training set using linear method is : **73.2833%**
The performance on test set using linear method is : **71.7%**

For the FaceScrub Dataset, we built a two layer neural network with the following structure using Tensorflow

[![Capture.png](https://s14.postimg.org/b6h9guqsh/Capture.png)](https://postimg.org/image/r4pz6zl0d/)




