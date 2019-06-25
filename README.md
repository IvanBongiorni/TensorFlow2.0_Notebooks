Author: Ivan Bongiorni, Data Scientist at GfK; [LinkedIn](https://www.linkedin.com/in/ivan-bongiorni-b8a583164/).

# TensorFlow 2.0 Tutorial



Welcome to my TensorFlow 2.0 tutorial.
Recently, Google released (the alpha version of) TensorFlow 2.0. As I'm trying to move from the 1.x and lern the new, I'll upload all my progresses on this repo.

The training of models is based on TensorFlow's **eager execution** method. I'll try to minimize referencese to Keras.


## Contents:

1. [Basic Classifier](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0_01_basic_Classifier.ipynb):  implementation of a **feed forward Classifier** with simple, full-Batch Gradient Descent in **Eager execution**.

2. **TensorFlow2.0_02_MiniBatch_Gradient_Descent**:  implementation of Mini-Batch Gradient Descent.

3. **TensorFlow2.0_03_Save_and_Restore_models**:  shows how to train a model, save it, then restore it and keep training.

4. **TensorFlow2.0_04_Autoencoder_for_Dimensionality_Reduction**:  implementation of a stacked Autoencoder.


### WARNING:
In this Notebook I will just skim through the main theoretical arguments related to Deep Learning. I will assume you already know of things like: dense/fully connected layers, gradient descent, dropout, regularization techniques, convolutional and pooling layers, autoencoders, ... you name it. It is mostly about models implementation, not about the theory behind them.



### Coming Soon:

- Early stopping
- Dynamic Learning Rate
- Regression tasks
- Use the TensorBoard
- Run TensorFlow 2.0 on Google Colab
- A basic Convolutional Neural Network
- Denoising Autoencoder

