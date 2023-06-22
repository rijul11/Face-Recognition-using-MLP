# Face-Recognition-using-PyTorch

**About the dataset**: \
[*Labeled Faces in the Wild*](http://vis-www.cs.umass.edu/lfw/) dataset consists of face photographs designed for studying the problem of unconstrained face recognition. The original dataset contains more than 13,000 images of faces collected from the web.

**Agenda**:
* In this programming challenge, you will be performing face recognition on the *Labeled Faces in the Wild* dataset using PyTorch.
* First, you will do Principal Component Analysis (PCA) on the image dataset. PCA is used for dimentionality reduction which is a type of unsupervised learning.
* You will be applying PCA on the dataset to extract the principal components (Top $k$ *eigenvalues*).
* As you will see eventually, the reconstruction of faces from these *eigenvalues* will give us the *eigen-faces* which are the most representative features of most of the images in the dataset.
* Finally, you will train a simple PyTorch Neural Network model on the modified image dataset.
* This trained model will be used prediction and evaluation on a test set.
