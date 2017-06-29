# Face-Recognition

Trained 25 face images (each having a dimension of 425 by 425) by implementing the Eigenface Algorithm in Python. Performed Principal Component Analysis (PCA) to get the Eigenvectors of the covariance matrix of the training images.
Reconstructed the training faces by selecting top 2, 5 and 15 Eigenvectors.
Tested the algorithm on 32 images. Projected each test image on top 2, 5 and 15 Eigenvectors and classified it as a face or nonface. Recognized the face images by using Eucledian distance to find the closest training image.
