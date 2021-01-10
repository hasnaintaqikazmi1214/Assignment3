# Assignment3
# CV Assignment 3

# Topic:
  Improve VGG16 performance to classify Natural Scenes by implementing Augmentation and Tranfer Learning.
  
# Introduction:
  
  Building an image classification pipeline using CNN to classify the natural scenes images into dif-
  ferent classes. We can use CNN architecture of our own choice, i.e. build VGG, or ResNet style
  architecture using primitive layers or call in the pre-implemented architecutes available in Keras /
  Pytorch.
  Our contribution is the thorough evaluation of network by applying augmentation on the dataset to generalize the network on unseen data. This was done by           introducing multiple augmentation types such as rotation, share and brightness etc. The data was augmented and feed to the network. 
  Beacuse of fine tunning of the augmentated data and learning rate, we get got accuracy with lessor iterations.
  
# Goal:
  
   We have a natural scenes images dataset, which need to be classify on 6 classes i.e Building, Forest, Glaciers, Mountains, Sea, street.
   The dataset is available on two platform, i.e Google drive and Kaggle
 
   Google Drive link: https://drive.google.com/file/d/1-57yNOSE5deGj4IwOa_Y5vXLxD72ihqH/view -> accesible using seecs email only
   Kaggle Link:       https://www.kaggle.com/puneet6060/intel-image-classification/version/2
 
   Our goal is to classify images to classes using VGG and get better perfomances/ accuracy by applying data Augmentation technique.
# VGG Achitecture:
![alt text](https://neurohive.io/wp-content/uploads/2018/11/vgg16-neural-network.jpg)

# Implemented Code:
Comments are given with code for better understanding.

# Evaluating Accuracy and Loss:

# Model Wieghts:

# Load Pre-train Weights:
pre_train_weights = keras.models.load_model("weights.h5")
