# Tomato Leaf Disease Prediction

A Deep Learning project that classifies tomato leaf diseases using
computer vision and transfer learning.\
The model analyzes leaf images and predicts the type of disease to help
in early detection and crop protection.

------------------------------------------------------------------------

## Overview

This project focuses on image classification using deep learning
techniques.

We:

-   Performed data preprocessing
-   Applied image transformations
-   Built a custom PyTorch dataset
-   Used transfer learning with a pretrained model
-   Trained and evaluated the model
-   Visualized performance metrics

The goal is to accurately classify tomato leaf diseases and support
agricultural decision-making.

------------------------------------------------------------------------

## Technical Highlights

-   Deep Learning (CNN-based image classification)
-   Transfer Learning using EfficientNetV2-S
-   PyTorch training pipeline
-   Train/Test split (80/20)
-   Performance tracking (accuracy & loss)
-   Visualization of training results

------------------------------------------------------------------------

## Installation

### 1️ Clone the repository

``` bash
git clone https://github.com/MajedAlsulami/Tomato-Leaf-Disease-Prediction.git
cd Tomato-Leaf-Disease-Prediction
```

### 2️ Install required libraries

``` bash
pip install -r requirements.txt
```


------------------------------------------------------------------------

## Usage

Download the dataset (automatically handled using KaggleHub).

Run the notebook:

``` bash
jupyter notebook Tomato_Leaf_Disease_Prediction.ipynb
```

Execute cells in order:

-   Import libraries
-   Download dataset
-   Preprocess images
-   Train model
-   Evaluate performance
-   Visualize results

------------------------------------------------------------------------

## Libraries and Technologies

-   Python
-   PyTorch
-   Torchvision
-   NumPy 
-   Matplotlib
-   Scikit-learn
-   KaggleHub

------------------------------------------------------------------------

## Dataset

Dataset downloaded from Kaggle:

**tomato-leaf-disease-dataset-6-classes**

### Classes:

-   Tomato Early Blight
-   Tomato Healthy
-   Tomato Late Blight
-   Tomato Leaf Yellow Curl Virus
-   Tomato Mold
-   Tomato Septoria Leaf Spot

------------------------------------------------------------------------

## Analysis Workflow

### 1️ Data Loading

-   Dataset downloaded using KaggleHub
-   Loaded into image folders

### 2️ Data Preprocessing

-   Image resizing
-   Normalization
-   Train/Test split

### 3️ Model Building

-   Loaded pretrained EfficientNetV2-S
-   Modified final classification layer

### 4️ Model Training

-   Loss Function: CrossEntropyLoss
-   Optimizer: AdamW
-   Trained for multiple epochs

### 5️ Model Evaluation

Evaluation Metrics:

-   Accuracy
-   Training Loss
-   Validation Loss

Higher accuracy = Better performance

------------------------------------------------------------------------

## Key Features

-   Transfer learning for high performance
-   Clean PyTorch pipeline
-   Automated dataset handling
-   Visual performance tracking
-   Scalable for other plant diseases

------------------------------------------------------------------------

## Project Structure

    ├── Tomato_Leaf_Disease_Prediction.ipynb
    ├── README.md
    ├── requirements.txt

------------------------------------------------------------------------

## What I Learned

-   How to apply transfer learning in computer vision
-   Building custom datasets in PyTorch
-   Importance of preprocessing for images
-   Training and evaluating deep learning models
-   Visualizing training performance

------------------------------------------------------------------------

## Future Improvements
-   Deploy model using Streamlit or Flask
-   Add real-time image prediction

------------------------------------------------------------------------

## License

This project is licensed under the MIT License.

------------------------------------------------------------------------

## Contributing

Contributions are welcome!

-   Fork the repository
-   Create a new branch
-   Make improvements
-   Submit a Pull Request

------------------------------------------------------------------------

## Questions

If you have any questions or feedback:

-   Email: majedsaadalsulami@gmail.com 
-   GitHub: [MajedAlsulami](https://github.com/MajedAlsulami)

------------------------------------------------------------------------

 If you found this project useful, consider giving it a star!
