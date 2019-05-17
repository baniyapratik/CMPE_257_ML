# CMPE_257_ML
CNN for pothole detection

# Description
I trained CNN from scratch to view and analyze the accuracy from scratch over 1300 dataset.
Then again i used a pre-trained Model, MobileNet which has already been trained over 10K imgenet to compare the accurancy.

# Data collection
- Used google
- driving around using gopro
- youtube streets

# Training Steps
- Batch Normalization, improves accuracy and decreases overfitting
- Dropout, to reduce variance
- Activation function: ReLu, cheap function for unlinearity and to avoid vanishing gradient
- Augmentation, adding more data set
- AveragePool looks more smooth than MaxPool, but MaxPool is better for Deep Neural Network training
- Grayscale 
- Padding to cover the stride discrepancies over the edges
- Used 3x3 filter
- 20 epochs for training



