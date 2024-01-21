# Image Captioning with CNN and RNN

## Overview

This repository contains a deep learning model for image captioning, combining Convolutional Neural Networks (CNN) for object extraction and Recurrent Neural Networks (RNN) for sentence generation. The model has been trained on a dataset of 50,000 images to enable the extraction of objects from images and generate corresponding textual descriptions.

## Features

- **CNN for Object Extraction:** Utilizes Convolutional Neural Networks to extract relevant objects from input images.
- **RNN for Sentence Generation:** Employs Recurrent Neural Networks to generate descriptive sentences based on the extracted objects.
- **Flask Application:** Provides a user-friendly interface for users to input images and receive corresponding textual captions.

## Usage

### Requirements

- Python 3.x
- Dependencies listed in `requirements.txt`

### Installation

  Clone the repository:

   ```bash
   git clone https://github.com/your-username/image-captioning.git
   cd image-captioning
python app.py


models weights/: Contains the CNN and RNN model implementations.
storage/: Directory for storing the training dataset and sample images
static/: Static files for the Flask application.
templates/: HTML templates for the Flask application.
app.py: Flask application script.
caption.py: model prediction script
