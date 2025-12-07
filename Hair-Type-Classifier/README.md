# Hair Type Classifier

This folder contains my hair type classification project for the course **ITAI 2277 – Artificial Intelligence Resources**.  
The goal of this project is to build a simple convolutional neural network (CNN) that can classify different hair types using images.

## Overview
The notebook `hair_classifier_model.ipynb` includes:
- Image loading and preprocessing  
- Dataset organization by hair type (Straight, Wavy, Curly, Kinky, Dreadlocks)  
- A CNN model with MobileNetV2 as the backbone  
- Data augmentation to improve generalization  
- Model training and validation  
- A classification report and confusion matrix  
- A function for predicting a single hair image  

## How It Works
1. Images are loaded from the `Hairdata/` folder and split into training and validation sets.  
2. A MobileNetV2-based model is trained to recognize hair type categories.  
3. Evaluation metrics show how well the model performed.  
4. A helper function can be used to test the model on new images.

## Purpose
This notebook demonstrates:
- Working with machine learning datasets  
- Applying transfer learning using MobileNetV2  
- Running a full machine learning workflow in Python  
- Producing a functional classifier that can be improved in future work  

## Notes
This is a **local version** of the notebook (not Colab-based).  
It can be opened and run in:
- Jupyter Notebook  
- Jupyter Lab  
- VS Code  
- Google Colab (optional)  
