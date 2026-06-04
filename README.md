# LightFracNet: Bone Fracture Detection

## Overview

This project focuses on detecting bone fractures from X-ray images using a deep learning approach. It uses wrist and forearm images from the MURA dataset and applies image preprocessing techniques to improve the quality of input data and overall model performance.

## Objective

The goal of this project is to build a model that can assist in identifying fractures in medical images in a simple and effective way.

## Approach

* Enhanced image quality using CLAHE (contrast enhancement)
* Applied edge detection using the Canny algorithm
* Built and trained a deep learning model using TensorFlow/Keras
* Evaluated the model using training and validation data
  
## Dataset

* MURA dataset (wrist and forearm images)
* The dataset is not included in this repository due to size limitations
* It can be downloaded separately from Kaggle
  
## Tools and Technologies

* Python
* TensorFlow / Keras
* OpenCV
* NumPy, Pandas
* Matplotlib
  
## How to Run

1. Clone this repository
2. Open the notebook in Google Colab or Jupyter
3. Install the required libraries
4. Run all cells step by step
   
## Results

* Training Accuracy: 90%
* Validation Accuracy: 81%
* Testing Accuracy: 81.2%
  
The model performs well on clear fracture cases, with some limitations in borderline cases.

## Sample Output

<img width="2546" height="1400" alt="fig5_gradcam (1)" src="https://github.com/user-attachments/assets/96e9d695-7ef6-472e-a4d3-3645b1812f42" />


## Notes

Make sure the dataset is downloaded and the correct path is set before running the notebook.

## Future Improvements

* Improve performance using transfer learning (ResNet, EfficientNet)
* Increase dataset size for better generalization
* Deploy the model as a web application
  
## Author
Sanchana Asmi B
