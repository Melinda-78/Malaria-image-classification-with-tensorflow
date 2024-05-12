# Malaria-image-classification-with-tensorflow
Introduction
 This project utilizes TensorFlow, an open-source machine learning framework developed by Google, to create a model for classifying blood smear images as either uninfected or parasitized with malaria.

Dataset
The dataset used for this project is sourced from the TensorFlow Image libraries and consists of approximately 27,500 cell images. These images are obtained from thin blood smear slide images of segmented cells. The dataset is divided into two classes:
1.Parasitized: Blood smear images containing cells infected with malaria.
2.Uninfected: Blood smear images containing cells without malaria infection.

Project Goal
The primary objective of this project is to develop a machine learning model capable of accurately classifying blood smear images as either uninfected or parasitized with malaria. This classification task is vital in medical diagnosis and research, aiding in the early detection and treatment of malaria.

Project Structure
The project is structured as follows:
1.Data Preparation: The dataset is preprocessed and organized into directories for training and evaluation.
2.Model Implementation: TensorFlow is used to define and train a convolutional neural network (CNN) model for image classification.
3.Model Evaluation: The trained model is evaluated on a separate test dataset to assess its performance and accuracy.
