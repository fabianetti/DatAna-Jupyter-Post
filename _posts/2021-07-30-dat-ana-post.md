# Deep Learning 9 Questions of Life

By answering the following nine questions, I'll be one step closer to finding the true secret of the Zebras.

![image](/images/zebra.png "Scail, the Zebra")

## 1 - Can we always use a random sample for a validation set?

No, when trying to make a prediction for the future, there is no point of predicting a random value in the past. In that case the validation set needs to consist of only the latest values.

## 2 - What is overfitting?

When training a model for too long or without enough data, the model remembers the prior predictions, without learning the traits that defined the decision.

## 3 - What is a metric? How does it differ from loss?

Loss is the value that the model tries to minimize, a metric is printed after each epoch for the user to see how the model performed. Especially in a classification problem, the loss value might change slightely while the prediction (and with it the metric) remains the same.

## 4 - How can pretrained models help?

Pretrained Models are used in Transfer Learning

## 5 - What is the head of a model?

The Neural Network?

## 6 - What kinds of features do the early layers of a CNN find?

In first layer it's just edges and gradients, in the second layer circles, semi-circles and repeating patterns can be found, in the third layer text, persons, repeating geometric patterns. From layer 4 onwards the features become distinct like dog faces.

## 7 - Are image models only useful for photos?

No, sound, mouse movent, viruses, etc can be converted into images.

## 8 - What is an architecture?

The mathematical function of a model that uses input data and parameters.

## 9 - What is a segmentation?

The model classifies every pixel of an image.

# What did I learn?

Having made some experiences from the BA with Image Processing the general idea was no news to me. However, I didn't know about the exact termination, like architecture or segmentation.
