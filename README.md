Multilayer Perceptron for classifcation analysis

The Model is built in #python using torch and keras modules

The original data from the patients are not available. This is a three class multiclassification problem.
Users can upload any data and modoy code accordingly

Brief Model details:
4 input features;
two hidden layers with 64 neurons; 
Relu activation functions in layers and multiclass output (thrre classes) probability classifier using a SoftMax function;
Adaptive Adam optimised learning rate; Binary cross entropy loss function with typical stochastic gradient descent;

Split data to Train and test data at 0.8/0.2 proportion, segmentation of train data in batches (batch size =8) for 1500 epochs. 
Repeat split of data and independently model fit for 100 times (Num_experiments).

antoniosdougalis@gmail.com
