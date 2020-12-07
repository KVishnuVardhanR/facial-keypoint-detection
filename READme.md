# Facial Keypoints Detection
The objective of this task is to predict keypoint positions on face images. This can be used as a building block in several applications, such as:

- tracking faces in images and video
- analysing facial expressions
- detecting dysmorphic facial signs for medical diagnosis biometrics / face recognition

# Requirements
Google Colab, PyTorch

# Training and Testing
- The dataset can be found in [Kaggle's Facial Keypoints
 Detection](https://www.kaggle.com/c/facial-keypoints-detection).
- This dataset is given in csv format, and has upto 30 facial keypoints which are to be used for training.
- Before feeding our data to neural net, first check if we have any null values in the dataset.
- We can either drop all the null values or impute them.
- Define a PyTorch Model to train our data and Valid it before saving the model.
- As we are trying to predict the facial keypoints, we have to use regression loss functions to train the data.
- Save the best fit model and test it on the test data and finally visualize the outputs.

# Further Improvisation
- For further Improvisation, we can use K-Fold Cross Validation techniques to improve the models performance.

 
   