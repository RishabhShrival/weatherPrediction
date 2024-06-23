# WeatherPrediction

## Project Overview
Weather prediction using image data with two different model architectures: a basic neural network and ResNet50. This project leverages a dataset of weather images to train models that can predict weather conditions from images.

## Dataset
The dataset used for this project can be downloaded from [Kaggle](https://www.kaggle.com/datasets/jehanbhathena/weather-dataset). It contains a folder named "dataset" which has multiple subfolders with images corresponding to different weather conditions.

## Pre-trained Models
Download the pre-trained models from the links below:
- **ResNet50 Model:** [Download](https://drive.google.com/file/d/1470tuoSzCXq_OCl1rsMKvMlW2CpIRn0e/view?usp=sharing)
- **Sequential Model:** [Download](https://drive.google.com/file/d/14TsV1m0m4inFUofZDhrZnzHF7XoYnV_d/view?usp=sharing)

## Training the Models

### Basic Neural Network Architecture
The `weather2.ipynb` notebook is used for training a model with a basic neural network architecture. Running this notebook will generate the `sequential.h5` file (trained model). Alternatively, you can directly download the trained model from the link provided above.

### ResNet50 Architecture
The `resnet_model_train.ipynb` notebook is used for training a model with the ResNet50 architecture. The pre-trained model can be downloaded from the link provided above.

**Note:** Go through the code in the notebooks and comment/uncomment lines as per your need.

## Running the Prediction Model Locally
To host the weather prediction model on your local system, use the `modelfile.py` script located in the `./file upload/` directory. This script will take any image as input and predict the weather condition.

## Usage Instructions
1. Download the dataset from the Kaggle link provided above.
2. Use the `weather2.ipynb` and `resnet_model_train.ipynb` notebooks to train the models or download the pre-trained models from the provided links.
3. To run the prediction model locally, execute the `modelfile.py` script.

Ensure you have the required libraries installed as specified in the notebooks.

Feel free to customize the code as needed to fit your requirements. Happy predicting!
