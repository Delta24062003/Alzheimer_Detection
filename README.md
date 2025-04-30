# Alzheimer_Detection
Leveraging MRI scans to detect Alzheimer's disease using CNN and vision transformers, aimed at enhancing diagnostic accuracy and supporting early intervention.

The app is live here: [Streamlit App Deployed Link !!](https://alzheimer-disease-by-amit.streamlit.app/)

## Introduction
This repository contains a deep learning framework designed to detect Alzheimer's disease using MRI scan images. The project aims to assist radiologists and medical professionals in early diagnosis through automated image analysis.

## Project Description
Alzheimer's disease is a progressive neurodegenerative disorder where early diagnosis is pivotal yet challenging. MRI scans are vital for detecting cerebral structural changes indicative of Alzheimer's. This project utilizes advanced deep learning architectures, including CNN based ResNet-50, EfficientNet, and Vision Transformers, which are trained, validated, and tested on a dataset of MRI scans to discern intricate patterns linked to the disease.

This project consists of two main parts:

PyTorch Modeling: Jupyter notebooks that contain the modeling work using PyTorch, including the creation, training, and validation of a CNN model, EfficientNet model and vision transformer for alzheimer's disease detection.
Streamlit App: The model was deployed on streamlit and is available for use.


## Repository Structure
```
.
├── Data
├── Models
│   ├── alzheimer_cnn_model.pth       # CNN model for Alzheimer's detection
│   └── alzheimer_efficientnet_model.pth  # EfficientNet model for Alzheimer's detection
├── Notebooks
│   ├── alzheimer-detection.ipynb     # Main Jupyter notebook for the project
│   └── data_explore.ipynb            # Notebook for data exploration and visualization
├── README.md   
├── Requirements.txt
├── Src
│   ├── alzheimer_efficientnet_model.pth  # Model file (duplicate, should review)
│   └── app.py                         # Streamlit application for deploying the model
└── Visualizations
    └── class_distribution.png        # Visualization of the dataset class distribution
```

## Installation
To set up your environment to run this code, you will need Python 3.8+ and the following packages:

Install dependencies: pip install -r model/requirements.txt
Explore the Jupyter notebooks in the `Notebooks` directory to understand the model development process.

## Usage
To run the Streamlit app:

```bash
streamlit run Src/app.py
```

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your enhancements.

## Credits
- Kaggle for Brain MRI data.
