# Flower Classification Using Convolutional Neural Network (CNN)
This project involves building and training a deep learning model for classifying images of flowers using TensorFlow. The model employs a Convolutional Neural Network (CNN) architecture to perform multi-class classification across a dataset of labeled flower images. The key steps in this project include data preprocessing, model building, training, evaluation, and visualization of results. The dataset used for training and testing the model consists of several categories of flower images. The dataset can be found at TensorFlow Flower Dataset. It contains images belonging to 5 different classes:
- Daisies
- Dandelions
- Roses
- Sunflowers
- Tulips
The images will be loaded using TensorFlow’s data pipeline API. The data is then split into training and validation sets.

The model is a Convolutional Neural Network (CNN) built using TensorFlow's Keras API. The architecture is as follows:
- Input layer: Receives flower images.
- Convolutional layers: Extract features from the images using filters.
- Pooling layers: Reduce the spatial dimensions of the feature maps.
- Dense (fully connected) layers: Classify the images based on the learned features.
- Output layer: Contains neurons equal to the number of flower categories.

Training the Model
- Data Augmentation: To improve the generalization of the model, data augmentation techniques like random flips, rotations, and zoom are applied.
- Optimizer: Adam optimizer is used to minimize the categorical cross-entropy loss.
- Training Process: The model is trained on the training dataset with early stopping to prevent overfitting. The validation accuracy and loss are monitored during training.

**Result**: The model achieves a reasonable accuracy on the flower dataset.

![image](https://github.com/user-attachments/assets/bbbf99d7-b21c-4a3a-93b4-79f650569bf2)
