Author: Ivan Bongiorni, Data Scientist at GfK; [LinkedIn](https://www.linkedin.com/in/ivan-bongiorni-b8a583164/).

# TensorFlow 2.0 Tutorial



Welcome to my TensorFlow 2.0 tutorial.
Recently, Google released (the alpha version of) TensorFlow 2.0. As I'm trying to move from the 1.x and lern the new, I'll upload all my progresses on this repo.

The training of models is based on TensorFlow's **eager execution** method. I'll try to minimize referencese to Keras.


## Contents:

1. [Basic Classifier](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0_01_basic_Classifier.ipynb):  implementation of a **feed forward Classifier** with simple, full-Batch Gradient Descent in **Eager execution**.

2. [MiniBatch_Gradient_Descent](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0_02_MiniBatch_Gradient_Descent.ipynb):  training a model with **Mini Batch Gradient Descent**.

3. [Save and Restore models](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0_03_Save_and_Restore_models.ipynb):  how to train a model, save it, then restore it and keep training.

4. [Autoencoder for Dimensionality Reduction](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0_04_Autoencoder_for_Dimensionality_Reduction.ipynb):  implementation of a stacked **Autoencoder for dimensionality reduction** of datasets.

5. [Convolutional Neural Network](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0_05_Convolutional_Neural_Network.ipynb): a basic **Convolutional Neural Network** for multiclass classification.

6. [Recurrent Neural Network](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0_06_RNN_many2one.ipynb): implementation of a **many_to_one forecasting RNN**.

### WARNING:
In this Notebook I will just skim through the main theoretical arguments related to Deep Learning. I will assume you already know of things like: dense/fully connected layers, gradient descent, dropout, regularization techniques, convolutional and pooling layers, autoencoders, ... you name it. It is mostly about models implementation, not about the theory behind them.



### Coming Soon:

- Early stopping
- Dynamic Learning Rate
- Regression tasks
- Use the TensorBoard

- RNN - many-to-many
- RNN - multivariate regressor

- Denoising Autoencoder
- Variational Autoencoder

