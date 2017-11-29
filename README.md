
# Machine learning And Artificial Intelligence

![Alt text](ml_hierarchy.PNG?raw=true "Optional Title")

1. **Supervised Learning**: Here Both the features and the lables are provided at the time of training the model.
      - **Regression**: In simple is finding the best fit line Ex: __Linear Regression__
      - **Classification**: The way of classification of data into classes. Some of the famous algorithm like __Knn__ and __SVM__ are used.
2. **Unsupervised Learning**: In this type only the Features are provided and left to the machine to identify the lable.
     - **Flat**: Here the programmer specifies the number of classes Ex: __K Means__
     - **Hierarchial**: Here it is left to the machine to decide on the number of classes Ex: __Mean Shift__
     
# Neural Networks

![Alt text](neural_net.PNG?raw=true "Optional Title")

In a neural network, The input is fed from the input layer,each node has an activation function which outputs based on the fed input, weight and bias.

This output is fed into the hidden layers, and the output is obtained through output layer.
![Alt text](cnn.PNG?raw=true "Optional Title")

**Convolution neural Networks**: In this type of neural networks the input is fed into the __convolution layer__ whose main function is to get activated if necessary and does the mapping accordingly.

Later this mappings is fed to the __pooling layer__, whose main function is to reduce the collection of output to a common output. Usually Max Polling is used, which will output the maximum of all the values in a given area.

Finally the output is fed to the fully connected layers.

During the training phase the output from the network is compared with the actual output to find the error, and the weights and bias are adjusted accordingly so that the error is reduced, this technique is called __backpropogation__. 

# Technologies to know to get started with machine learning
1. __Python__ : Simple to learn and easy to use interpreted language.
2. __Pandas__ :  To handle the data, basically to read and write the data
3. __Numpy__: Most of the machine learing libraries require numpy array to operate on.
4. __Scikit learn__ : Library for well know machine learning algorithms and functions
5. __TensorFlow__ : Machine learning libray developed by google, supports GPU also.





