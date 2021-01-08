# Multilayer-Neural-Network-Python-Forward-Backward-prop-plus-Gradient-Descent-Weight-Initialization
Purpose: Implementation of Neural network forward, backward propagation from scratch with Xavier and He Weight initialization and ADAM and RMSProp Optimizers

*This code implements various functions using PYTHON/Numpy used in calculating Weight Initialization, Forward Propagation, Backwar Propagation, Gradient decent and Prediction for Neural Network

*You can set your own size of Neural Network for as minimum as two layers (input and output) or add more hidden layers in between

*The capabilities implemented in this code are: 

    Activation Functions: Sigmoid, Relu, Leaky Relu, Tanh, Softmax 
    
    Initialization:  Random, He and Xavier
    
    Optimizers:   Simple Gradient Decent, RMSProp and ADAM
    
    Regularization:  Lambda regularization and Dropout
    
    Forward propagation and Backward propagation (Sigmoind and Relu)
    
    Prediction:   Calculating Mean Squared Error (MSE), Mean Absolute Erro (MAE) and Accuracy
    
*The code is a simple illustration of usage of Sigmoid Binary Classification and "as-is" does not have capabilities for Softmax.  If you would like to use this with Softmax, i suggest you implement the the Softmax Gradient and Backprop function and also tune the code.

*This is not the most efficient implementation of the code as i seldomly am using for loops (instead of vectorized implementations), however please feel free to change the implemnetation to make it more Structurally efficient and also efficient from the Complexity Order perspective

*The majority of the idea and some of the code is from Andrew NG's DeepLearning AI course

*I have commented the code as much as possible so that it is clear what is being implemented

In this code iam using, the Cat versus dog picture with two training and test sets of shapes (209, 64, 64, 3) and (50, 64, 64,3) shapes with the following format (m, pic_height, pic_width, RGB_Channels).   I am using a sigmoid classsifier with 32 mini_batch to minimize the Binary Classification Cost.  For these two datasets i am using the following datasets from Andrew NG's course train_catvnoncat, test_catvnoncat.

*If you are not using image classification i suggest you comment out the portion of the minibatch code

I have used to run the model for Epochs=1000, with normal Gradient decent at a learning rate of (alpha=0.01).  I have used "He" initialization to initialize the weights.  I am posting the results here which is for demonstration purposes only.   If you are running this code again with the same parameters, i suggest you just run this to Epochs =300 as further Epochs would not add any significant value to the minimizing cost and improving accuracy
