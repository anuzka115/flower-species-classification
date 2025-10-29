# Image Classifier – PyTorch

This project is part of Udacity's **AI Programming with Python Nanodegree**.  
The goal is to build an **image classification model** using **PyTorch**, train it on a flower dataset, and use the trained network to predict the class of new images.

The project includes two main components:

- **Model Training:**  
  A neural network is trained using transfer learning. The model learns to classify flower images into 102 different categories. During training, the script reports loss, accuracy, and saves checkpoints.

- **Prediction Application:**  
  A command-line tool loads a saved checkpoint and predicts the most likely flower name for a given input image, along with the class probability.

The final deliverable is a fully functional image classifier that can train on a dataset, save the model, and perform inference on new images using a terminal command.
