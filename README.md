# Face-Recognition using Eigen faces

Trained 25 face images (each having a dimension of 425 by 425) by implementing the Eigenface Algorithm and performed the following steps:
1) Calculation of the mean face. 
2) Performed Principal Component Analysis (PCA) to get the Eigenvectors of the covariance matrix of the training images.
3) Reconstructed the training faces by selecting top k = 2, 5 and 15 Eigenfaces (eigenvectors which correspond to the largest eigenvalues).
4) Tested the algorithm on 32 images. Projected each test image on top k = 2, 5 and 15 Eigenvectors and classified it as a face or nonface.  Recognized the face images by using Eucledian distance to find the closest training image.
5) Plotted a graph representing percent classification error rate as a function of the number of Eigenvectors(k)
