# -WSI_Image_Analysis
A two-part digital pathology pipeline for extracting image patches from Whole Slide Images (WSIs) and training a machine learning model to classify histopathology images. Built using OpenSlide and scikit-learn, this project was developed as part of an academic assignment in computational pathology.
# 🧠 WSI_Image_Analysis

This repository focuses on digital pathology, specifically the preprocessing and classification of Whole Slide Images (WSIs) using machine learning techniques.

## 📌 Overview

1. `WSI2Patch_allSlide.ipynb`  
   - Extracts 256×256 image patches from `.svs` Whole Slide Images using OpenSlide  
   - Applies grayscale filtering, resizing, and saves patches for modeling

2. `image_classification.ipynb`  
   - Loads preprocessed patches and trains an SVM classifier  
   - Evaluates model performance using scikit-learn  
   - Uses structured folders for multi-class classification

## 🔧 Tools & Libraries Used

- Python
- OpenSlide, PIL, OpenCV
- scikit-learn, NumPy, Pandas
- matplotlib, skimage
- Google Colab + Google Drive integration

## 💡 How to Use

1. Extract patches using `WSI2Patch_allSlide.ipynb` from your `.svs` files
2. Organize patches into class-labeled folders
3. Run `image_classification.ipynb` to train and evaluate the model

## 📂 Repo Structure
WSI_Image_Analysis/ ├── notebooks/ │ ├── WSI2Patch_allSlide.ipynb │ └── image_classification.ipynb ├── data/ # Not included in repo ├── requirements.txt └── README.md

This project was completed as part of an academic assignment on digital pathology and machine learning.

