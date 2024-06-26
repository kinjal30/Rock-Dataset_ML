# Rock-Dataset_ML

Welcome to image analysis and classification project! This Python script leverages techniques like PCA and K-Means clustering to analyze and group images based on their features. 
It also includes a neural network for image classification, providing accurate categorization of images. Check out the code to explore how it simplifies image analysis and enhances classification accuracy!

# Description:

Data Preprocessing: Images are loaded and preprocessed using the load_and_preprocess_images function. The images are resized to a specified dimension and converted into arrays.

Principal Component Analysis (PCA): PCA is applied to reduce the dimensionality of the image data while preserving important features. The number of principal components required to preserve 95% of the variance is determined and used for further analysis.

Visualization: Original images and their reconstructions using PCA are visualized to demonstrate the effectiveness of dimensionality reduction.

Clustering: K-Means clustering is performed on the image data to identify clusters or groups of similar images. The optimal number of clusters is determined using the Elbow method.

Gaussian Mixture Model (GMM): GMM clustering is applied to the image data to identify underlying probability distributions and cluster assignments.

Neural Network Training: A neural network model is built and trained using the image data to classify images into predefined categories. The model's training progress and performance are visualized using accuracy and loss metrics.

Model Evaluation: The trained model's activations are compared with human rankings using Procrustes analysis to assess the model's performance and alignment with human perception.


# Technologies Used:

Python: The primary programming language for developing the entire project.

TensorFlow and Keras: Used for deep learning tasks such as image preprocessing, building neural network models, and extracting features from images.

Scikit-learn: Utilized for various machine learning tasks such as dimensionality reduction (PCA), clustering (K-Means, Gaussian Mixture Models), and manifold learning (t-SNE, Locally Linear Embedding, MDS).

Matplotlib: Employed for data visualization purposes, including plotting images, scatter plots, and other visualizations.

NumPy: Used for numerical computations and array manipulations, particularly in handling image data.

Pandas: Used for organizing and analyzing data, particularly in generating tables to display analysis results.

Google Colab: Utilized as the development environment for running Python code, leveraging its cloud-based computational resources.

Image Processing Libraries (e.g., PIL, scikit-image): Employed for loading, processing, and transforming image data.
