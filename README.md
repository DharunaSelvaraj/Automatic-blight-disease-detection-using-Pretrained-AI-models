Plant Disease Detection: Early and Late Blight in Potato and Tomato Plants

Overview:

This project focuses on detecting early and late blight in potato and tomato plants using advanced AI models. Leveraging pretrained models such as VGG-16 and ResNet-9, we have achieved impressive accuracy rates of 98% and 99% respectively. This tool aims to assist farmers and agricultural experts in early identification and treatment of plant diseases, thus enhancing crop yield and quality.

Features

-Detection of early and late blight in potato and tomato plants.

-Utilizes VGG-16 and ResNet-9 pretrained models for high accuracy.

-User-friendly interface for uploading plant images and receiving diagnosis.

-Detailed reporting of results with probability scores.

Tech Stack

-Frontend: Flask (Python web framework)

-Backend: TensorFlow/Keras, PyTorch

-Models: VGG-16, ResNet-9

-IDE: Jupyter Notebook, PyCharm

Prerequisites

-Python 3.7 or higher

-TensorFlow

-PyTorch

-Flask

-OpenCV

-NumPy

-Pandas

Installation

Clone the repository

bash

git clone https://github.com/DharunaSelvaraj/plant-disease-detection.git

cd plant-disease-detection

Create a virtual environment

bash

python -m venv venv

source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install dependencies

bash
Copy code

pip install -r requirements.txt

Download pretrained models

Ensure you have the VGG-16 and ResNet-9 models downloaded. You can use the scripts provided in the models/ directory to download and set up the models.

Run the application

bash

flask run

Usage

Launch the Application

Run the Flask application using the command flask run.

Open your web browser and navigate to http://127.0.0.1:5000.

Upload Plant Images

Use the provided interface to upload images of potato or tomato plants.

The system will process the image and provide a diagnosis indicating whether the plant is affected by early or late blight.

View Results

The results will include the type of blight detected and the probability score.

Detailed reports are generated for each uploaded image.

Model Details

VGG-16

Accuracy: 98%

Description: VGG-16 is a convolutional neural network model with 16 layers. It is known for its deep architecture and effectiveness in image classification tasks.

ResNet-9

Accuracy: 99%

Description: ResNet-9 is a residual network with 9 layers. It addresses the vanishing gradient problem and allows for training of very deep networks with improved accuracy.
Contribution

We welcome contributions! If you have suggestions, improvements, or bug fixes, please fork the repository and create a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
