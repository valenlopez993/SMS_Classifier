# SMS Classifier

This project was part of a [Free Code Camp Machine Learning course](https://www.freecodecamp.org/learn/machine-learning-with-python/#how-neural-networks-work) where I built a Recurrent Neural Network (RNN) to classify SMS messages as either *spam* or *ham* (non-spam).

The dataset used for training the model was obtained from the Free code camp Machine Learning course resources.

The preprocessing of the text data involved first tokenization that was performed using the class Tokenizer of TensorFlow, and then padding of the sequences due to the different sizes of each SMS text passed to the model.

The model architecture was built with Keras and it consists of three layers:

- Embedding input layer
- Long short-term memory (LSTM) layer
- A 1-neuron Dense output layer with a sigmoid activation function to produce a binary output between 0 and 1, where 0 represents *ham* and 1 represents *spam*
Of all the projects in the course, I found this one the most interesting and challenging due to all the notions I had to learn in order to preprocess the text data.

<p align="center">
  <img src="./docs/sms.png">
</p>
