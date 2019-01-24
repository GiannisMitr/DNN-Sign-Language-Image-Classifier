# DNN Sign Language Image Classifier
A deep neural network that classifies images with sign language numbers [0-5].     

An 3 hidden layer network is created, with RELU activations in all layers expect for the output layer that uses a Softmax function.      
 
Xavier initiallization is used for parameters and Adam optimization algorithm with mini-batches for training.     

Implemented as TensorFlow graph.

## Usage

Execute                      *sign_language_classifier*, by configuring *minibatch_size* and *num_epochs* parameters of function *model()* you can set the batch_size and the number of full passes through the training set.


The code will:
* Train the defined model for configurable mumber of iterations
* Use trained parameters to compute accuracy for train and test datasets
* Try to predict the label on a custom image provided by the user.


Inspiration and help from Coursera deeplearning specialization