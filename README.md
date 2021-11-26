# Product-Recommender-System
## Project Overview
This project is a recommender system of products which I downloaded from Kaggle. I have a CNN model called ResNET which is trained on a datadset called image NET. The ResNET model is used for feature extraction of the images I have used. The dataset has 44k images. First, I uploaded one image to compare it with another 44k images and 5 images which are closer to the uploaded one would be shown as recommendations. This processes with the help of Euclidean distance. The images flows through every layer of the ResNET model. The first layer will see primitive feature of an image, e.g., all tshirts have similar features. When I give all the images to the ResNET model then, for every image the model has a set of 2048 features. It becomes (44k, 2048) 2D arrays. Where 44k is the total number of images in the dataset and, 2048 is the number of features of each image. When  upload an image then the eclidean distace of each vector(array) is calculated and those images are shown in the recommendations which have minimum distance from the uploaded image.


[Project implementation](https://youtu.be/4HrzgE5m1Qc)
