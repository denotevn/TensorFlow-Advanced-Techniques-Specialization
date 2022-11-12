# Learning Objective
> Custom layers give you the flexibility to implement models that use non-standard layers. Practice building off of existing standard layers to create custom layers for your models.
   + Define a custom layer to include the activation function
   + Define a custom layer class by inheriting from the Layer class
   + Describe the two components of a custom layer
   + Describe what a custom layer can do that a lambda layer cannot
   + Use a lambda layer to customize a network layer
+ Examples lambda layers: 
   + ***tf.keras.layers.Lambda(lambda x: tf.abs(x))***
+ Trong bài này mình sẽ học viết hàm activation riêng cho model của bạn. Có vẻ sẽ hiệu quả hơn các hàm define sẵn trong tensoflow. hãy chờ xem !
+ Let's see C1_W3_Lab_1_lambda-layer.ipynb in floder week 3
![Examples](https://github.com/denotevn/TensorFlow-Advanced-Techniques-Specialization/blob/main/Course%201/Week%203/images/examples1.png)

# Coding your own custom Dense Layer
+ Examples: 
   + ![Layers](https://github.com/denotevn/TensorFlow-Advanced-Techniques-Specialization/blob/main/Course%201/Week%203/images/create%20custom%20layers.png)
   + With activation:
   + ![Activation](https://github.com/denotevn/TensorFlow-Advanced-Techniques-Specialization/blob/main/Course%201/Week%203/images/with%20activation.png)
# Lab assigment:
  + You will implement a simple quadratic layer and include it as part of a model. You will then train this model on the MNIST dataset.

