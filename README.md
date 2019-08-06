Author: Ivan Bongiorni, Data Scientist at GfK; [LinkedIn](https://www.linkedin.com/in/ivan-bongiorni-b8a583164/).

# TensorFlow 2.0 Tutorial



Welcome to my TensorFlow 2.0 tutorial.
Recently, Google released (the alpha version of) TensorFlow 2.0. As I'm trying to move from the 1.x and lern the new, I'll upload all my progresses on this repo.

The training of models is based on TensorFlow's **eager execution** method. I'll try to minimize referencese to Keras.


## Contents:

**Basic feed forward stuff**:

1. [Basic classifier](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__00.01_basic_Classifier.ipynb):  implementation of a **feed forward Classifier** with simple, full-Batch Gradient Descent in **Eager execution**.

2. [Mini batch gradient descent](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__00.02_MiniBatch_Gradient_Descent.ipynb):  training a model with **Mini Batch Gradient Descent**.

3. [Save and restore models](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__00.03_Save_and_Restore_models.ipynb):  how to train a model, save it, then restore it and keep training.

---

**Autoencoders**:

1. [Autoencoder for dimensionality reduction](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__02.01_Autoencoder_for_Dimensionality_Reduction.ipynb):  implementation of a stacked **Autoencoder for dimensionality reduction** of datasets.

2. Denoising Autoencoder

3. (see the convolutional Variational Autoencoder below)

---

**Convolutional Neural Networks**:

1. [basic CNN classfifier](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__03.01_Convolutional_Neural_Network.ipynb): a basic **Convolutional Neural Network** for multiclass classification.

2. Advanced CNN classifier with custom data augmentation

3. Mixed-CNN classifier

4. Variational Autoencoder, with conv layers for image generation.

---

**Recurrent Neural Networks**:

1. [LSTM many-to-one forecast model](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__04.01_RNN_many2one.ipynb)

2. LSTM many-to-many forecast model

3. Multivariate LSTM regression

---

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

