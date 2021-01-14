# Self-Driving-Car-using-Deep-Learning-and-Computer-Vision

The udacity has a software which we can use the directional key to drive a car in the track with en no of trainings. This software uses 3 cameras 2 on each sides and one on centre. 

This camera produces a image output and each image as its own steering angle, acceleration and braking as csv files . 

Then opencv is trained for detecting the lanes, MNIST is used for detecting the numbers, Then CNN is used for detecting the traffic signs. 

The model is trained in such a way that the car which is self driving adjust by itself to be in the centre of the lane. 

Using Behavioural cloning the various deeplearning model which is trained are combined and made the self driving car to drive. 
When it is trained it made to run in the udacity software of new track which is completely different.

Libraries used - Tensorflow-Keras, Numpy, Matplotlib, CV2, Random, Pandas, Imgaug.
