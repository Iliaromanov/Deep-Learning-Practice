# Deep-Learning-Practice
Practice problems and mini-projects involving neural networks. Includes my work from the Deeplearning.ai Neural Networks and Deep Learning online course. 


## Notes
### Tensorflow:
- Defining learning rate and decay in optimizer. Learning rate = the size of the steps model takes during SGD, Decay = how much the steps size decreases further into training; this is done to be more accurate when closer to the minimum
  ```python
  # Adam optimizer
  import tensorflow as tf
  
  optimizer = tf.keras.optimizers.Adam(lr=0.001, decay=1e-5)  # set learning rate = 1e-3 and decay = 1e-5
  ```
