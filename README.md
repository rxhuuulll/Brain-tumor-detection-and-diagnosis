# Brain-tumor-detection-and-diagnosis
This repository contains code for a machine learning project focused on classifying tumor images into two categories: "no_tumor" and "pituitary_tumor." The project uses Python and various libraries, including NumPy, OpenCV, and scikit-learn, to train and evaluate classification models. It also provides a simple visualization of the classification results.
Table of Contents
* Introduction
* Data
* Usage
* Results
* License
  
## Introduction
Tumor Image Classification is a project that aims to automatically classify medical images of the brain into two categories: images with "no tumor" and images with "pituitary tumor." The project involves preprocessing the image data, splitting it into training and testing sets, training machine learning models, and evaluating the model's performance.

## Data
The data used in this project is stored in the /content/drive/MyDrive/Projecttt/Training directory. The images are divided into two classes: "no_tumor" and "pituitary tumor." The data is loaded and preprocessed using OpenCV to ensure it is ready for machine learning.

## Usage
To use this project, follow these steps:

## Clone the repository:
bash
Copy code
git clone https://github.com/your-username/your-repo.git
Install the required Python libraries if you haven't already. You can use a virtual environment for this purpose.
bash
Copy code
pip install numpy pandas matplotlib opencv-python scikit-learn
Execute the provided code. Ensure that the paths to the image data and other variables are set correctly.

Train and evaluate the classification models. The project uses a logistic regression model and a support vector machine (SVM) for classification. You can modify the models or use other machine learning techniques as needed.

Visualize the results. The code includes code snippets for visualizing the classification results using matplotlib.

## Results
The project provides training and testing scores for the classification models. Additionally, there are visualizations of test images and their corresponding classifications.

## Sample output:

Training Score: 1.0
Testing Score: 0.9681274900398407
Total Misclassified Samples: 13

These results indicate the accuracy of the models and the number of misclassified samples in the testing dataset.

## License
This project is licensed under the MIT License. You are free to use and modify the code for your own purposes. Please review the LICENSE file for more details.

Feel free to contribute to this project by improving the code, adding new features, or enhancing the documentation. If you have any questions or suggestions, please open an issue or contact the project maintainers.
#### Rahul Mk
