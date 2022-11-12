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

