# covid-face-mask-detector

This project aims to detect face masks in images using a pre-trained MobileNetV2 deep learning model. The model is trained on a dataset of images of people wearing and not wearing masks, enabling it to recognize whether a person is wearing a mask in a given image.

Dataset Used: https://www.kaggle.com/datasets/prithwirajmitra/covid-face-mask-detection-dataset

## Requirements:
To run this project, the following libraries and frameworks are required:

### Python 3.6 or above
### TensorFlow 2.3 or above
### OpenCV
### NumPy
### Matplotlib
### sklearn 

## Installation:
The required libraries and frameworks can be installed using pip. Run the following command in the terminal:
pip install tensorflow opencv-python numpy matplotlib

## Output:
The output of the face mask detection system will be an image or video with bounding boxes around the faces detected, indicating whether or not a mask is being worn. The bounding box will be green if a mask is detected, and red if no mask is detected. The confidence score for mask detection will also be displayed in the top-left corner of the bounding box.

