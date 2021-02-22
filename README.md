# Deep-learning-Projects.

## RNN, GRU and NLP application on open sourse datasets.

### Toxic_comment_classification_using_CNN and using_LSTM model.
**A multiclass classification of comments with 6 possible labels.**
1. "severe_toxic"
2. "obscene"
3. "threat"
4. "insult"
5. "identity_hate"
6. "toxic"

**A comment classification has been done using CNN model. 1DConvnet is used for text classification.**

https://github.com/umairiqbal78/Deep-learning-Projects/blob/main/Toxic_comment_classification_using_CNN.ipynb

**A comment classification has been done using LSTM model. I used simple LSTM and Bidirectional LSTM for the good results**

https://github.com/umairiqbal78/Deep-learning-Projects/blob/main/Toxic_comment_classification_using_LSTM.ipynb

### sequence to sequence (urdu to eng) translation LSTM Model:
**This work has two parts. One is Encoder and the other is Decoder**
### Encoder:
Encoder is doing the job of learning the vocabulary of language. Word Embedding of GLOVE is used. And it's hidden states is also saved in the model. These hidden states further used in decoder model.
### Decoder 
It just translate the input using the hidden states of Encoder. Hidden states takes the previous memory of the input sequence which help to predict the translation.

https://github.com/umairiqbal78/Deep-learning-Projects/blob/main/seq2seq_urdu2eng_trans_LSTM.ipynb

### sequence to sequence translation on eng to turk with Attention technique:
**This Attention techniques includes a special technique of gathering a context of a sentence like a human. It includes following steps.**
1. Inputs are passed through the BiDirectional LSTM.
2. Hidden states are collected from inputs and concatenate them.
3. Those passed through Neural Network.
4. Output from Neural Network passed through from activation function and get weight (alpha).
5. All alphas are dotted to weight sum of hidden states.
6. N alphas from N inputs are combine and form a context of input.
7. Which is further passed through decoder to get the Output.

https://github.com/umairiqbal78/Deep-learning-Projects/blob/main/attention_LSTM.ipynb

### Poetry generator LSTM:
**This LSTM model is trained on poetry dataset. From the dataset model learn the pattern and structure of sentences. Which is used for predicting the poetry by hte model.**

https://github.com/umairiqbal78/Deep-learning-Projects/blob/main/poetry_LSTM.ipynb

### Source Code:

https://github.com/lazyprogrammer/machine_learning_examples

An online cource I followed for the all above projects is Deep Learning: Advanced NLP and RNNs

https://deeplearningcourses.com/c/deep-learning-advanced-nlp
