# Yolo-tomato
# Overview:
This project uses YOLO (You Only Look Once) machine learning algorithm to detect tomato fruits in images. The algorithm is trained using a custom dataset of tomato images. The project is implemented in Google Colab and utilizes Python, TensorFlow, Keras, and OpenCV.

# Instructions for Running the Code:
To run the code, follow the steps below:

Clone this GitHub repository to your local machine
Open Google Colab and upload the Jupyter notebook file named "YOLO_tomato_detection.ipynb" from the cloned repository
In the notebook, click on the "Runtime" dropdown menu and select "Run all"
The notebook will run and generate a set of results
The results include a set of images with bounding boxes drawn around the detected tomato fruits

# Dataset:
The custom dataset used for training the YOLO tomato detection model can be found in the "tomato_dataset" folder in this repository. The dataset consists of 500 images of tomato fruits. The images are of varying sizes and quality. The images are labelled with bounding boxes around the tomato fruits.

# Model:
The YOLO tomato detection model is defined in the "YOLO_tomato_detection.ipynb" notebook file. The model is trained using the custom dataset of tomato images. The model architecture consists of 53 convolutional layers and is trained for 50 epochs. The model achieves a mean average precision (mAP) of 0.85 on the test set.

# Results:
The results of the YOLO tomato detection model can be found in the "results" folder in this repository. The results include a set of images with bounding boxes drawn around the detected tomato fruits.

# Conclusion:
This project demonstrates the use of machine learning tools to detect tomato fruits in images. The YOLO algorithm is used to accurately detect tomato fruits in images with a high level of accuracy. The model can be further improved by training on a larger dataset of tomato images.
