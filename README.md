# Fashion-MNIST Simple CNN Parameter Experiment

This notebook explores the performance of a simple Convolutional Neural Network through experimentation with three key parameters:

* Filter Size
* Number of Features
* Batch Size


The CNN used here classifies fashion-MNIST images into one of the following nine categories:
0. T-shirt/top
1. Trouser
2. Pullover
3. Dress
4. Coat
5. Sandal
6. Shirt
7. Sneaker
8. Bag
9. Ankle Boot


The notebook begins by training a simple CNN as a baseline, and then uses this same CNN structure to perform a factorial experiment using a small selection of values for the three parameters listed above. 
Afterwards, the results of this experiment and the key takeaways are discussed. Additionally, a brief explanation of the function of each of these parameters is included for quick reference.
