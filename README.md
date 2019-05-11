# Image-Classification-with-Fashion-MNIST-and-CIFAR-10

## Summary

This is the final project for CSC219 - Machine Learning at California State University, Sacramento.

There are many models that can be used in the Image Classification task. However, not all models are created equal, and it is a challenge for students to understand and choose the correct models with the appropriate dataset. This project will implement various machine learning models, and examine different features extraction techniques to reduce the training time and improve
the performance of the models. The highlights of this project are gaining knowledge, data preprocessing, features extraction and applying the appropriate models on different dataset.

## Implementation
1. **Dataset**: The dataset used in this project are Fashion-MNIST and CIFAR-10. They are available on Keras and the following links:
  - Fashion-MNIST: https://github.com/zalandoresearch/fashion-mnist
  - CIFAR-10 : https://www.cs.toronto.edu/~kriz/cifar.html

2. **Data Preprocessing**: Each pixel in the image is normalized to have range between 0 and 1. The models below are applied to the dataset in the following ways:
  - Applying the models with the original data
  - Applying the models with PCA features extraction
  - Applying the models with Autoencoder features extraction

3. **Model**: The following models are used in this project, in accordance with the above data preprocessing steps:
  - SVM
  - KNN
  - Random Forest
  - Decision Tree
  - Convolutional Neural Network (CNN)

## Result:
Approach of using Autoencoder is better than PCA for boosting the performance of the model, especially using Autoencoder with SVM surpasses the performance of CNN model. These results can still be improved with the use of pretrained model or deeper autoencoder architecture

### Future Work:
- Modular the code for reproductivity
- Try transfer learning
- Try Residual Network
