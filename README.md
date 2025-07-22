Enhancing Pneumonia Detection in Chest X-Rays Using Ensemble Learning

This repository contains a deep learning project for the classification of chest X-ray images to detect pneumonia. The model leverages an ensemble of powerful, pre-trained Convolutional Neural Network (CNN) architectures to achieve high classification accuracy and robust performance. This work builds upon experience gained during a Deep Learning internship at the National Institute of Technology Puducherry.

📊 Results & Evaluation
The model's performance was rigorously evaluated to ensure accurate and reliable detection. High classification accuracy was achieved on the target Kaggle dataset.


Export to Sheets
🎯 Methodology
The project follows a comprehensive methodology to build an effective detection model:


Ensemble Model: A deep learning model was developed by creating an ensemble of powerful, pre-trained CNNs, including VGG16, ResNet, and Inception.


Transfer Learning: Transfer learning was implemented to fine-tune the pre-trained architectures on the chest X-ray dataset, significantly optimizing classification performance.

Image Preprocessing: To improve model accuracy and generalization, several image preprocessing techniques were conducted, including:

Data Augmentation 

Contrast Enhancement 

Image Normalization 


Performance Optimization: The project involved hyperparameter tuning and performance optimization to reduce overfitting and enhance model interpretability.

💻 Tech Stack
The project was developed using the following Python frameworks and libraries:

TensorFlow 

Keras 

OpenCV 

NumPy 

Matplotlib 

💾 Dataset
The model was trained and evaluated on a publicly available 

Chest X-Ray Images (Pneumonia) dataset from Kaggle. You can find the dataset 


here.

🚀 How to Run this Project
Clone the repository:


git clone https://github.com/MDheerajkumar123/pneumonia-detection-in-chest-xrays-using-DL-models.git
Navigate to the project directory:


cd pneumonia-detection-in-chest-xrays-using-DL-models
Install the required libraries:


pip install -r requirements.txt
(Note: You will need to create a requirements.txt file listing all the libraries from the Tech Stack section.)

Run the analysis: Open and run the Jupyter Notebook or Python script to train the model and see the results.
