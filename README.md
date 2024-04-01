# Rock-Dataset_ML

Welcome to image analysis and classification project! This Python script leverages techniques like PCA and K-Means clustering to analyze and group images based on their features. 
It also includes a neural network for image classification, providing accurate categorization of images. Check out the code to explore how it simplifies image analysis and enhances classification accuracy!

Description:

Data Preprocessing: Images are loaded and preprocessed using the load_and_preprocess_images function. The images are resized to a specified dimension and converted into arrays.

Principal Component Analysis (PCA): PCA is applied to reduce the dimensionality of the image data while preserving important features. The number of principal components required to preserve 95% of the variance is determined and used for further analysis.

Visualization: Original images and their reconstructions using PCA are visualized to demonstrate the effectiveness of dimensionality reduction.

Clustering: K-Means clustering is performed on the image data to identify clusters or groups of similar images. The optimal number of clusters is determined using the Elbow method.

Gaussian Mixture Model (GMM): GMM clustering is applied to the image data to identify underlying probability distributions and cluster assignments.

Neural Network Training: A neural network model is built and trained using the image data to classify images into predefined categories. The model's training progress and performance are visualized using accuracy and loss metrics.

Model Evaluation: The trained model's activations are compared with human rankings using Procrustes analysis to assess the model's performance and alignment with human perception.
