# Automatic Number Plate Recognition

## Project Overview

* This project develops an automated number plate recognition system using computer vision and deep learning. The system detects vehicles in an image or video stream, extracts the license plate region, and applies Optical Character Recognition (OCR) to read the plate characters. It leverages YOLO for detection and EasyOCR/Tesseract for text recognition. A Streamlit web application is provided for users to upload images or videos and view results in real time.

## Data Preprocessing

* Collected and annotated vehicle images for training number plate detection.

* Resized and normalized images to improve model performance.

* Applied data augmentation (rotation, brightness, noise) to increase dataset robustness.

## Detection & Extraction

* Used YOLOv8 for detecting vehicles and number plates in frames.

* Cropped detected plate regions and preprocessed them (grayscale, thresholding, denoising).

* Applied OCR (EasyOCR / Tesseract) to extract alphanumeric characters from plates.

## Modelling

* Trained YOLOv8 model for number plate detection.

* Integrated OCR pipeline for text recognition.

* Combined detection + recognition into an automated end-to-end workflow.

## Evaluation

* Evaluated detection accuracy using mAP (mean Average Precision).

* Measured OCR accuracy with character-level recognition rate.

* Achieved strong plate detection and recognition across varied lighting and angle conditions.

## Results

* Successfully detected and recognized number plates in both images and video streams.

* Delivered high detection accuracy and reliable OCR performance.

* Deployed an interactive Streamlit app for real-time number plate recognition.
