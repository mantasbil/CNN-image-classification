# Image classification using CNN

In this project convolutional neural network (CNN) is built to perform classification of images in [Cifar 10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset which consists of ten types of images - airplane, automobile, bird, cat, deer, dog, frog, horse, ship and truck.

TensorFlow package was used for creating the model.

Project was run on Google Colab using their NVIDIA-SMI GPU.

Neural network of this structure was built:
![image](https://github.com/user-attachments/assets/2b6dff9a-f9e9-4694-86f1-ce7a702bdb6e | width=100)

ReLu activation was used in convolutional and dense layers while Softmax was used for the output layer.

The final model was trained on 13 epochs as going further showed no improvements in performance on validation data.
The final model achieved quite good accuracy, correctly classifying 89% of training data and 80% of validation data.
The most common mistake made by the model was confusing cats and dogs.
