# Object Recognition Using COIL-100 Dataset

## Abstract

In this project, we present a comprehensive study on object recognition using the COIL-100 dataset. We developed a Deep Convolutional Neural Network (DCNN) model, employing batch normalization, max-pooling, and Softmax activation functions. The model underwent training for 50 epochs with varying batch sizes and was evaluated on an independent test dataset. Performance metrics such as accuracy, F1-score, ROC analysis, and precision-recall curves were used for a thorough assessment.

## Keywords

Layers, ADAM, Categorical Cross-Entropy loss, Batch size, ROC, F1-score.

## Problem Definition

The project addresses the creation of an effective DCNN model for object recognition in a dataset with 100 distinct object classes. Key considerations include optimal architecture, hyperparameter impact assessment, and selection of performance metrics.

## Methodology

1. Loading of dataset: Use Kaggle API to import the COIL-100 Database.
2. Data preprocessing: Normalize pixel values and one-hot encode images.
3. Model creation: Implement a DCNN model with ReLU activation and Softmax for classification.
4. Model training: Train the model over 50 epochs with varying batch sizes.
5. Model evaluation: Assess performance metrics using testing images.
6. Analysis of results: Interpret model performance.

## Model Description

The DCNN-ReLU model is designed for object recognition, featuring convolutional layers, batch normalization, max-pooling, and a fully connected layer with Softmax activation. It addresses the complexities of diverse object classes and computational constraints.

## Database

COIL-100 Dataset:
  - Input image: 128x128 pixels
  - No. of samples: 7200
  - No. of classes: 100

## Discussion and Comparison

The model achieved an accuracy of 99.86%. Various performance metrics, ROC-Curve, and Precision-Recall Curve were analyzed. Comparison with other models shows superior performance.

## Conclusion

The study successfully developed and evaluated a DCNN model for object recognition using the COIL-100 dataset. The model demonstrated adaptability, generalization abilities, and computational efficiency. Performance metrics provided a comprehensive evaluation, emphasizing the importance of DCNN models in real-world scenarios.

## Limitations

Despite the success, limitations include dataset representativity, hyperparameter sensitivity, and concerns regarding overfitting in limited labeled data scenarios.


