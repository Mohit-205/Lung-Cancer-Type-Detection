Lung Cancer Type Detection
This repository contains a MATLAB app for detecting the type of lung cancer based on images using a pre-trained Convolutional Neural Network (CNN). The application uses a dataset of lung cancer images, trains a deep learning model, and then uses that model to classify lung cancer types when provided with a new image.

Features
Image Upload: Users can upload lung cancer images via a simple interface.
Model Prediction: The app predicts the type of lung cancer based on the uploaded image.
Visualization: Displays the predicted type and provides a confusion matrix for model performance.
Pre-trained Model: The app uses a pre-trained deep learning model (saved as LungCancerModel1.mat) for predictions.
Project Components
MATLAB CNN Model: A convolutional neural network trained on a lung cancer image dataset.
App Interface: A graphical user interface (GUI) built using MATLAB App Designer.
Image Processing: The app preprocesses and resizes uploaded images for model prediction.
Model Evaluation: The app displays the model’s accuracy and confusion matrix.
Installation Instructions
MATLAB: Ensure you have MATLAB installed on your system. This project is compatible with MATLAB R2024b or higher.

Required MATLAB Toolboxes:

Deep Learning Toolbox (for CNN functionality)
MATLAB App Designer (for GUI creation)
Download the Project Files:

Clone or download the repository files.
Ensure you have the LungCancerModel1.mat file saved in your working directory or update the path to the file in the code.
Dataset
The app uses the IQ-OTHNCCD Lung Cancer Dataset (a sample lung cancer image dataset) for training the CNN model. The dataset contains lung cancer images categorized by type. Ensure that you have the dataset available in your local environment to proceed with training or using the pre-trained model.

User interface & working:

![1](https://github.com/user-attachments/assets/3de7ebc4-0f96-41d6-bce4-ad3e95f52b82)
![2](https://github.com/user-attachments/assets/87dca299-f019-4b7f-beb2-a2d2e61ff6d8)
