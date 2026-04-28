Project Overview
This project focuses on the automatic detection and classification of brain tumors using MRI images and deep learning techniques. A Convolutional Neural Network (CNN) based on the VGG-16 architecture is used to classify brain images into four categories:


Glioma Tumor


Meningioma Tumor


Pituitary Tumor


No Tumor


The system aims to assist medical professionals in early diagnosis, reducing manual effort and improving accuracy.


🎯 Objectives


Develop an automated system for brain tumor detection


Implement VGG-16 based CNN for classification


Improve performance using transfer learning


Achieve high accuracy in multi-class classification


Evaluate model using accuracy, precision, recall, and F1-score



 Methodology
The project follows a structured deep learning pipeline:


Data Collection – MRI brain tumor dataset


Preprocessing – Resizing and normalization


Data Augmentation – Rotation, flipping, brightness


Feature Extraction – Using pre-trained VGG-16


Model Training – CNN with transfer learning


Evaluation – Accuracy, confusion matrix, ROC


Prediction – Classifying new MRI images



Results


Accuracy: ~96–97%


High precision, recall, and F1-score


AUC Score: ~1.00 (Excellent performance)


Low training loss


High confidence predictions (~97%)


The model shows strong performance across all tumor classes with minimal misclassification.

Sample Outputs


Correct classification of MRI images


Confidence scores close to 97%


Effective detection of tumor types



Technologies Used


Python


TensorFlow / Keras


NumPy


OpenCV


Matplotlib & Seaborn


Jupyter Notebook



How to Run


Clone the repository:


Install dependencies:


pip install tensorflow keras numpy opencv-python matplotlib seaborn


Run the notebook:


jupyter notebook


Open:


brain_tumour_detection.ipynb

Advantages


High accuracy and reliable predictions


Automated detection reduces manual effort


Supports early diagnosis


Multi-class classification capability


Scalable and adaptable system



Limitations


Requires high computational resources


Depends on dataset quality


Needs real-world clinical validation


Limited interpretability (black-box model)



Applications


Medical diagnosis support


Hospital automation systems


Telemedicine


Medical research


AI-based healthcare solutions



Future Scope


Use advanced models (ResNet, EfficientNet)


Real-time implementation


3D MRI analysis


Mobile/web deployment


Explainable AI (Grad-CAM)



Conclusion
This project successfully demonstrates the use of deep learning in medical imaging. The VGG-16 based model provides a fast, accurate, and automated solution for brain tumor detection, making it a valuable decision-support tool for healthcare professionals.

Author
Astha Jha
Supervisor:
Dr. Nitin Singh Singha
Assistant Professor, ECE
NIT Delhi

References
Includes research papers on deep learning, CNNs, and medical imaging (see report for full list).
