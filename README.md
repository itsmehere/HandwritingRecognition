# Handwriting Recognition

An AI to recognize digits from handwriting

## TensorFlow:

Using [tensorflow](https://tensorflow.org)'s, neural networks, this model identifies handwritten digits with an accuracy of 98.25%.

Inside `handwriting.py` is the structure for the neural network used that currently performs as so:

```
Epoch 1/10
1875/1875 [==============================] - 21s 11ms/step - loss: 0.2905 - accuracy: 0.9134
Epoch 2/10
1875/1875 [==============================] - 23s 12ms/step - loss: 0.0930 - accuracy: 0.9741
Epoch 3/10
1875/1875 [==============================] - 21s 11ms/step - loss: 0.0658 - accuracy: 0.9827
Epoch 4/10
1875/1875 [==============================] - 20s 11ms/step - loss: 0.0511 - accuracy: 0.9856
Epoch 5/10
1875/1875 [==============================] - 24s 13ms/step - loss: 0.0386 - accuracy: 0.9890
Epoch 6/10
1875/1875 [==============================] - 20s 11ms/step - loss: 0.0307 - accuracy: 0.9913
Epoch 7/10
1875/1875 [==============================] - 20s 11ms/step - loss: 0.0248 - accuracy: 0.9925
Epoch 8/10
1875/1875 [==============================] - 20s 11ms/step - loss: 0.0211 - accuracy: 0.9939
Epoch 9/10
1875/1875 [==============================] - 30s 16ms/step - loss: 0.0168 - accuracy: 0.9952
Epoch 10/10
1875/1875 [==============================] - 20s 11ms/step - loss: 0.0152 - accuracy: 0.9957
313/313 - 1s - loss: 0.0895 - accuracy: 0.9825
```

`hr_model` is a trained neural network that you can use with `recognition.py` to draw digits and classify them(unless you want to modify the `handwriting.py`` in which case you'd have to resave the model).

## [MNIST](https://en.wikipedia.org/wiki/MNIST_database):

MNIST is a dataset in TensorFlow that contains many sample handwritten digits that we can use to train our neural network([read more](https://en.wikipedia.org/wiki/MNIST_database))