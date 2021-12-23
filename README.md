# CNN-to-predict-locations-of-my-previous-trips

In this project, I used frames from videos I took in different trips I had to 4 different countries. The goal is to create a deep neural network to predict the location based on frames from a certain video.

* Uploaded and resized +4000 frames of videos from personal travels using OS and openCV.
* Created custom tensors from the pictures using Pytorch (250 batches of 16 tensors).
* Built a deep neural network (2 CNN and 3 Linear) to identify the location images.
* Achieved 98.31% accuracy on training set and 96.5% on testing set.
* Visualized a batch of testing data with Matplotlib and Mathematical methods.


# Resources Used
* Python Version: 3.7
* CUDA Toolkit 11.5.119 
* Packages and Libraries: pandas, numpy, matplotlib, pytorch, openCV, OS, matplotlib.
# Data used
* Videos from personal previous travels of 4 locations:
  1. Bali, Indonesia. Video of a man cutting open a fresh coconut in the amazing coast of the island.
  2. Seoul, Korea. While visiting the historical Gyeongbokgung Palace, I recorded a video of the beautiful fortress.
  3. Penang Island, Malaysia. A breath-taking sunset from the roof of a 34-floor modern residential building.
  4. Istanbul, Turkey. A 360° view of the 8th wonder of the world, Hagia Sophia.

# Data preparation
* Converted four videos to pictures frame by frame.
* Uploaded and resized the pictures for uniformity.
* Created separate training and testing sets.
# CNN architecture:
* Model information using torchinfo:

![image 1](https://github.com/YoussefAithaddou/CNN-to-predict-locations-of-my-previous-trips/blob/main/model%20info.PNG)

###### Model layers:
* 2x CNNs
* 2x Pooling layers
* 3x Linear neurons
###### Hyper parameters:
* Batch size: 16
* Epochs: 3
# Model Evaluation:
* Accuracy on training set is 98.28 %
* Accuracy on testing set is 93.50 %
# Sample visualization:
* I used a batch of test data (4 images from each location) to asses how the model predict the location of each frame:

![image 2](https://github.com/YoussefAithaddou/CNN-to-predict-locations-of-my-previous-trips/blob/main/result%20sample.png)

* This model achieved a high accuracy rate with a small training sets due to the fact that all pictures are relatively similar to each other (frames of the same video). In this particular sample, the model manages to accurately identify each location the frames belong to. That is, on average we can accurately identify pictures at a ratio of 14.96 frames in each batch of 16.
