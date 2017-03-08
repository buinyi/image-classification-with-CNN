# CIFAR-10 Image Classification with CNNs
In this project images from [CIFAR-10 dataset](https://www.cs.toronto.edu/%7Ekriz/cifar.html) are classified using a deep learning network with some convolutional layers implented with TensorFlow.

The project was done at the Udacity's [Deep Learning Nanodegree Foundation Program.](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101)

Implemented in the ipython notebook:
   - Convolutional layers with ReLU activation
   - Maxpooling layers
   - Flatten layer
   - Fully connected layers with ReLU activation
   - Output layer

The final classifier consisting of 4 convolutional layers (some of them with max pooling) and 2 fully connected layers had xx% testing accuracy.

The structure of the network and the weight initialization approach were inspired by Udacity's forums and community and Andrej Karpathy's [lecture.](https://www.youtube.com/watch?v=LxfUGhug-iQ) 

In this project weight initialization proved to be very important for the model performance. For the most weights, I used `tf.nn.truncated_normal` with different standard deviations ranging from 0.05 to 0.1.

More useful informaton on image classification can be found [here](http://rodrigob.github.io/are_we_there_yet/build/classification_datasets_results.html).