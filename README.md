Author: Ivan Bongiorni, Data Scientist at GfK; [LinkedIn](https://www.linkedin.com/in/ivan-bongiorni-b8a583164/).

# TensorFlow 2.0 Tutorial


This is a collection of my Notebooks on TensorFlow 2.0

The training of models is based on TensorFlow's **eager execution** method. I'll try to minimize referencese to Keras.
## Summary of Contents:
- Basic feed forward stuff
- Autoencoders
- Convolutional Neural Networks
- Recurrent Neural Networks

---
---

## Contents:

**Basic feed forward stuff**:

1. [Basic classifier](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__00.01_basic_Classifier.ipynb):  implementation of a **feed forward Classifier** with simple, full-Batch Gradient Descent in **Eager execution**.

2. [Mini batch gradient descent](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__00.02_MiniBatch_Gradient_Descent.ipynb):  training a model with **Mini Batch Gradient Descent**.

3. [Save and restore models](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__00.03_Save_and_Restore_models.ipynb):  how to train a model, save it, then restore it and keep training.

0. Train a Neural Network with frozen layers

---

**Autoencoders**:

1. [Autoencoder for dimensionality reduction](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__02.01_Autoencoder_for_Dimensionality_Reduction.ipynb):  implementation of a stacked **Autoencoder for dimensionality reduction** of datasets.

2. Denoising Autoencoder (see CNN section below).

0. Recurrent Autoencoder (see RNN section below).

---

**Convolutional Neural Networks**:

1. [Basic CNN classifier](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__03.01_Convolutional_Neural_Network.ipynb): a basic **Convolutional Neural Network** for multiclass classification.

2. Advanced CNN classifier with custom data augmentation.

3. Mixed-CNN classifier.

4. Denoising Autoencoder.

---

**Recurrent Neural Networks**:

1. [LSTM many-to-one forecast model](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__04.01_RNN_many2one.ipynb)

2. [LSTM many-to-many forecast model](https://github.com/IvanBongiorni/TensorFlow2.0_Tutorial/blob/master/TensorFlow2.0__04.02_RNN_many2many.ipynb)

3. Multivariate LSTM regression.

0. Recurrent Autoencoders.

0. Seq2seq models.

---


### Coming Soon:

- RNN - multivariate regressor
- Denoising Autoencoder
- A lot of NLP stuff with RNNs
