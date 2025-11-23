# Karpathy Zero to Hero Exercises

I am following the famous Karpathy Zero to Hero Youtube series ( link : https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)

In this repo, I am solving all the exercises suggested in the video. Feel free to use them for reference.

## 1_building_micrograd
Exercises were mentioned inline jupyter notebook. You can directly read the notebook itself

## 2_makemore_bigrams
Exercises:

E01: train a trigram language model, i.e. take two characters as an input to predict the 3rd one. Feel free to use either counting or a neural net. Evaluate the loss; Did it improve over a bigram model?

E02: split up the dataset randomly into 80% train set, 10% dev set, 10% test set. Train the bigram and trigram models only on the training set. Evaluate them on dev and test splits. What can you see?

E03: use the dev set to tune the strength of smoothing (or regularization) for the trigram model - i.e. try many possibilities and see which one works best based on the dev set loss. What patterns can you see in the train and dev set loss as you tune this strength? Take the best setting of the smoothing and evaluate on the test set once and at the end. How good of a loss do you achieve?

E04: we saw that our 1-hot vectors merely select a row of W, so producing these vectors explicitly feels wasteful. Can you delete our use of F.one_hot in favor of simply indexing into rows of W?

E05: look up and use F.cross_entropy instead. You should achieve the same result. Can you think of why we'd prefer to use F.cross_entropy instead?

E06: meta-exercise! Think of a fun/interesting exercise and complete it.

```Note : For E06 I tested performance of CPU vs GPU. My Mac MPS GPU gave 3x faster performance```

## 3_makemore_mlp
Building a multi-layer perceptron (MLP) character-level language model:

E01: Training MLP - Implementing and training a neural network with embeddings and hidden layers

E02: Uniform initialization - Exploring different initialization strategies and their impact on training

## 4_batchnorms_mlp
Understanding and implementing batch normalization:

E01: Implementing Batchnorm - Adding batch normalization layers to improve training stability and performance

## 5_backprop_ninja
Deep dive into backpropagation mechanics:

Becoming a backprop ninja - Manual implementation of backpropagation to understand the gradient flow through neural networks
