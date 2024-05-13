# Malaria-image-classification-with-tensorflow
INTRODUCTION:
 This project utilizes TensorFlow, an open-source machine learning framework developed by Google, to create a model for classifying blood smear images as either uninfected or parasitized with malaria.

DATASET:
The dataset used for this project is sourced from the TensorFlow Image libraries and consists of 27558 cell images. These images are obtained from thin blood smear slide images of segmented cells. The dataset is divided into two classes:
1.Parasitized: Blood smear images containing cells infected with malaria.
2.Uninfected: Blood smear images containing cells without malaria infection.

PROJECT GOAL:
The primary objective of this project is to develop a machine learning model capable of accurately classifying blood smear images as either uninfected or parasitized with malaria. This classification task is vital in medical diagnosis and research, aiding in the early detection and treatment of malaria.

PROJECT STRUCTURE:
The project is structured as follows:
1.Data Preparation: The dataset is preprocessed and organized into directories for training and evaluation.We vizualize the images and covert the tensors to numpy arrays before building the model.
Prior to model bulding we perform the following steps:
a)Data Processing:This is done to ensure the images are of a consistent size and to normalize the pixel values.
b)Data Augmentation:This is used to overcome the class imbalance and overfitting problem specifically in medical imaging applications as data set is very less
2.Model Implementation: TensorFlow is used to define and train a convolutional neural network (CNN) model for image classification.It is able to classify whether a blood smear is uninfected or parasitized
3.Model Evaluation: The trained model is evaluated on a separate test dataset to assess its performance and accuracy.
