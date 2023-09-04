# Lung_Cancer_Detection

This project aims to detect lung cancer from CT-Scan images using deep learning techniques. The dataset used in this project contains CT-Scan images of Adenocarcinoma, Large cell carcinoma, Squamous cell carcinoma, and normal cells.

# Dataset Description

The CT-Scan images are in jpg or png format to fit the model. The dataset contains four main folders:

**Lung Adenocarcinomas**: contains CT-Scan images of Adenocarcinoma of the lung. Adenocarcinoma is the most common form of lung cancer, accounting for 30% of all cases overall and about 40% of all non-small cell lung cancer occurrences.

**Lung Squamous Cell Carcinomas**: contains CT-Scan images of Squamous cell carcinoma of the lung. This type of lung cancer is responsible for about 30% of all non-small cell lung cancers, and is generally linked to smoking.

**Lung Benign Tissue**: contains CT-Scan images of normal cells.

# Technologies Used

This project was implemented using the following technologies:

**TensorFlow** and **Keras**: for building and training the deep learning model.

**Inception V3**: pre-trained models used for transfer learning.

**PIL**, **OpenCV**: for image processing.

**Matplotlib**: for visualizing the training and validation results.


# Model Architecture

The deep learning model used in this project is a convolutional neural network (CNN). The model consists of several layers including convolutional, max pooling, batch normalization, and dense layers. Transfer learning is used by initializing the model with pre-trained weights from the above-mentioned pre-trained model.
