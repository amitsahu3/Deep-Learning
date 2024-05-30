# Reccurent Neural Networks (RNN)
Recurrent Neural Network(RNN) is a type of Neural Network where the output from the previous step is fed as input to the current step.
*  In traditional neural networks, all the inputs and outputs are independent of each other.
*  Still, in cases when it is required to predict the next word of a sentence, the previous words are required and hence there is a need to remember the previous words.
*  The main and most important feature of RNN is its Hidden state, which remembers some information about a sequence.

<img alt="What-is-Recurrent-Neural-Network" height="330" src="https://media.geeksforgeeks.org/wp-content/uploads/20231204125839/What-is-Recurrent-Neural-Network-660.webp" width="660">

# RNNs vs Traditional ANNs
* **Artificial neural networks** that do not have looping nodes are called feed forward neural networks. Because all information is only passed forward, this kind of neural network is also referred to as a multi-layer neural network.Information moves from the input layer to the output layer – if any hidden layers are present – unidirectionally in a feedforward neural network.
* The fundamental processing unit in a **Recurrent Neural Network (RNN)** is a Recurrent Unit, which is not explicitly called a “Recurrent Neuron.” This unit has the unique ability to maintain a hidden state, allowing the network to capture sequential dependencies by remembering previous inputs while processing. Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) versions improve the RNN’s ability to handle long-term dependencies.

<img alt="RNN-vs-FNN" height="330" src="https://media.geeksforgeeks.org/wp-content/uploads/20231204130132/RNN-vs-FNN-660.png" width="660">

### **Types Of RNN**
There are four types of RNNs based on the number of inputs and outputs in the network.
1. One to One :
2. One to Many : describe one image in multiple words
3. Many to one : categorize many words (sentences) as positive or negative ; i.e sentiment analysis
4. Many to many : Translate one language into another

[Read more] https://www.geeksforgeeks.org/introduction-to-recurrent-neural-network/





