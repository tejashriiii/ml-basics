learning machine learning and deep learning through mini projects and documenting them in one. //personal notes

what i learnt in each colab file?:

1. Iris-data
   - learnt how to load, explore, and visualize data.
   - used RandomForestClassifier for classification of 3 flower's classes, also tried a simple logistic regression to compare results

2. Titanic-data
   - practiced cleaning data, handling missing values and other eda basics
   - encoding categorical features since machine need numbers for input, feature engineering
   - learnt how to test model and how preprocessing the data changes the output.

3. regression-from-scratch
   - understood the concept behind regression model
   - cost function and gradient descent implementation manually
   - also compared results with sklearn regression model.

4. mnist
   - working with image data for basic deep learning practice (mnist 0-9 digits dataset)
   - how neurons work and what their structure should be (input layer, hidden layer, output layer), activation functions
   - normalization values to bring them in a 0-1 range
   - learnt overfitting, accuracy, image dataset handling (//todo:use cnn)

5. icon
   - used fashion_mnist dataset
   - built simple CNN model for classification of items, understood pooling layer, convolution layer and dropout concepts
   - valuated and compared with a normal ANN model for same dataset (without CNN i.e. with feature extraction)
  
6. readingModel
   - text data conversion and vectorization, Eda and feature extraction for a huge amount of data(100k books from goodreads)
   - used simple clustering algorithm and classes for each type of reader

7. cvcv - cv2 basics
   - imported 2 different types of images (uint8, float32, etc) to compare, and learnt image representation and conversion using cv2(BGR to RGB to GRAYSCALE), and channels along with getting rid of redundant channels.
   - performed statistical analysis and log transform(important for SAR backscatter data) and normalization to [0,1] since many ML models' inputs are in 0's and 1's. later performed spatial feature analysis using sobel edge detection(x&y) to better understand where things are in the image.
   - more SAR specific topics like speckle noise filtering and Patch/tile extraction + Data augmentation could be explored next.
