# Traffic Sign Classification using HOG and K-Nearest Neighbors

This project performs binary image classification to distinguish between traffic sign images and non-traffic sign images using a machine learning pipeline.

## 🔍 Feature Extraction with HOG

Histogram of Oriented Gradients (HOG) was used to extract visual features from the images. This technique captures edge and gradient structures, which are useful for identifying objects like traffic signs.

## 🧠 Classification with K-Nearest Neighbors

The extracted features were classified using the K-Nearest Neighbors (KNN) algorithm. K-Fold Cross Validation was applied to determine the optimal value of **K**, and the best performance was achieved with **K = 2**.

## ✅ Evaluation Results

- **Accuracy**: 100%
- **Precision, Recall, F1-Score**: 1.00
- **Confusion Matrix**: No False Positives or False Negatives

This result shows that the HOG + KNN combination can work very well for binary image classification when the visual features are clear and structured.
