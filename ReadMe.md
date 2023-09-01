# Automatic Number Plate Detection

This project demonstrates automatic number plate detection using the EasyOCR library and OpenCV. It allows you to extract and visualize text information from images containing vehicle number plates.

1. Install the necessary libraries.
2. Use EasyOCR to detect text in an image.
3. Annotate detected text with bounding boxes and labels.
4. Display the annotated image.

## Prerequisites

Before running the code, make sure you have the required libraries installed:

```bash
!pip3 install torch torchvision torchaudio
!pip install easyocr
```

## Usage
Clone this repository to your local machine.

Replace IMAGE_PATH in the code with the path to the image you want to process.

Run the Python script to perform automatic number plate detection and visualization.

The code will display the image with detected number plates outlined and the extracted text printed to the console.

## Dependencies
 EasyOCR: Used for text recognition.
 
 OpenCV: Used for image processing.
 
 Matplotlib: Used for image visualization.
