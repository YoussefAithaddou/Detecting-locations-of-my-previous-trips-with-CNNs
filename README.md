# CNN-to-predict-locations-of-my-previous-trips

In this projects, I used frames from videos I took in different trips I had to 4 different countries. The goal is to create a deep neural network to predict the location based on frames from a certain video.

* Uploaded and resized +4000 frames of videos from personal travels using OS and openCV.
* Created custom tensors from the pictures using Pytorch (250 batches of 16 tensors).
* Built convolutional neural networks (2 CNNs and 3 Linears) to identigy the location images.
* Acheived 98.31% accuracy on training set and 96.5% on testing set.
* Visualized a batch of testing data with Matplotlib and Mathematical methods.

# Resources Used
* Python Version: 3.7
* CUDA Toolkit 11.5.119 
* Packages and Libraries: pandas, numpy, matplotlib, pytorch, openCV, OS, matplotlib.
# Data used
* Videos from personal previous travels of 4 locations:
  1. Bali, Indonesi. Video of a man cutting open a fresh cocunuts in the amazing coast of the island.
  2. Seoul, Korea. While visiting the historical Gyeongbokgung Palace, I recorded a video of the beautiful fortress.
  3. Penang island, Malaysia. A breathtaking sunset from the roof of a 34 floor modern residential building.
  4. Istanbul, Turkey. A 360° view of the 8th wonder of the world, Hagia Sophia. 

# Data preparation
* Converted four videos to pictures frame by frame.
* Uploaded and resized the pictures for unifromity.
* Created separate training and testing sets.
# CNN architecture:
###### Model layers:
* 2x CNNs
* 2x Pooling layers
* 3x Linear neurons
###### Hyper parameters:
* Batch size:
* Epochs:
* 
# Model Evaluation:
###### Decision tree###### Decision tree
###### Decision tree###### Decision tree
* Mean Absolute Error: 0.062
* Accuracy: 0.94
###### Support vector machine:
* Mean Absolute Error: 0.092
* Accuracy: 0.91

![image 2](https://github.com/YoussefAithaddou/CNN-to-predict-locations-of-my-previous-trips/blob/main/result%20sample.png)
