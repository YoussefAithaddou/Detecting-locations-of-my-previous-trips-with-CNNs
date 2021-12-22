# CNN-to-predict-locations-of-my-previous-trips

In this projects, I used frames from videos I took in different trips I had to 4 different countries. The goal is to create a deep neural network to predict the location based on frames from a certain video.

* Scraped over 500 pages of reviews and ratings from RotenTomatoes.com for the movie Mortal Kombat 2021 using python and selenium.
* Cleaned and converted data into a matrix of token counts with the help of sklearn's CountVectorizer.
* Optimized Naive-Bayes multiclass classifier using GridsearchCV to choose the optimal parameters.
* Classified data and predicted the movie ratings based on the written reviews.

# Resources Used
* Python Version: 3.7
* Packages: pandas, numpy, sklearn, matplotlib, seaborn, selenium.
* ChromeDriver 95.0.4638.10 [download](https://chromedriver.chromium.org/downloads).
# Data used
* Videos from personal previous travels of 4 locations:
  1. Bali, Indonesi. Video of a man cutting open a fresh cocunuts in the amazing coast of the island.
  2. Seoul, Korea. While visiting the historical Gyeongbokgung Palace, I recorded a video of the beautiful fortress.
  3. Penang island, Malaysia. A breathtaking sunset from the roof of a 34 floor modern residential building.
  4. Istanbul, Turkey. A 360° view of the 8th wonder of the world, Hagia Sophia. 


# Data preparation
* Removed missing values.
* Sampled data for analysis and visualization.
* We visualize the correlation between attributes:
![image 1](https://github.com/YoussefAithaddou/Predcition-of-Airline-Passengers-Satisfaction/blob/main/Correlation%20Matrix.png)
* SVM is a slow algorithm, thus we used a sample of 5000 rows from the original data as opposed to 100.000 samples sued for the logistic regression and Decison tree models.
# Classifcation models:
###### Logistic regression:
* Mean Absolute Error: 0.161
* Accuracy: 0.84
###### Decision tree:
* Mean Absolute Error: 0.062
* Accuracy: 0.94
###### Support vector machine:
* Mean Absolute Error: 0.092
* Accuracy: 0.91

![image 2](https://github.com/YoussefAithaddou/Predcition-of-Airline-Passengers-Satisfaction/blob/main/Confusion%20matrix.png)
