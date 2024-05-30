# Convolution Neural Networks (CNN)
Recurrent Neural Network(RNN) is a type of Neural Network where the output from the previous step is fed as input to the current step.
*  In traditional neural networks, all the inputs and outputs are independent of each other.
*  Still, in cases when it is required to predict the next word of a sentence, the previous words are required and hence there is a need to remember the previous words.
*  The main and most important feature of RNN is its Hidden state, which remembers some information about a sequence.

<img alt="What-is-Recurrent-Neural-Network" height="330" src="https://media.geeksforgeeks.org/wp-content/uploads/20231204125839/What-is-Recurrent-Neural-Network-660.webp" width="660">
# RNNs vs Traditional ANNs
* **Artificial neural networks** that do not have looping nodes are called feed forward neural networks. Because all information is only passed forward, this kind of neural network is also referred to as a multi-layer neural network.Information moves from the input layer to the output layer – if any hidden layers are present – unidirectionally in a feedforward neural network.
* The fundamental processing unit in a **Recurrent Neural Network (RNN)** is a Recurrent Unit, which is not explicitly called a “Recurrent Neuron.” This unit has the unique ability to maintain a hidden state, allowing the network to capture sequential dependencies by remembering previous inputs while processing. Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) versions improve the RNN’s ability to handle long-term dependencies.
**Classify an image as cat or dog using CNN**
## CNN architecture
Convolutional Neural Network consists of multiple layers like the input layer, Convolutional layer, Pooling layer, and fully connected layers.



The Convolutional layer applies filters to the input image to extract features, the Pooling layer downsamples the image to reduce computation, and the fully connected layer makes the final prediction. The network learns the optimal filters through backpropagation and gradient descent


  ## Neural Networks
  * Neural networks are made of input neuron, hidden layers and output neurons
  * Each input neuron represents a feature and has weight and bias given to it
  * hidden layers add a lot of power as inout layers neurons are feeded to them in various combination of features
  * these hidden neurons have acivation function that allows the signals to pass based on their importance
  * after multiple combinations and passes it finally reaches the output neuron
  * actual and calculated values are compared and cost function is calculated
  * then weights are adjusted backwards in order to improve the accuracy so as to minimise the co function
  * one round through the whole dataset is called one **_epoch_**

  [Read more](https://www.geeksforgeeks.org/introduction-convolution-neural-network/)

  


