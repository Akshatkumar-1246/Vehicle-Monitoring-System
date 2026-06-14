# Automatic Number Plate Recognition (ANPR) System

An AI-based vehicle monitoring system that detects number plates, extracts license numbers, tracks vehicle movement, and automatically maintains entry and exit records.

## Overview

This project uses computer vision and deep learning to build an Automatic Number Plate Recognition system. A custom YOLOv8 model was trained on a number plate dataset from Roboflow for accurate license plate detection. The detected plate region is processed using OCR to extract the vehicle registration number.

The system identifies whether a vehicle is entering or exiting based on its movement direction and stores all records automatically with timestamps.

## Features

- Real-time number plate detection
- Custom trained YOLOv8 model
- OCR-based license number extraction
- Vehicle IN/OUT tracking
- Automatic Excel record generation
- Timestamp-based vehicle logging
- Image and video processing support
- Live webcam detection
- Interactive Streamlit web interface

## Technologies Used

- Python
- YOLOv8
- OpenCV
- Roboflow
- OCR (Pytesseract)
- Pandas
- Streamlit
- Excel Data Management

## Workflow

1. Train YOLOv8 model on custom license plate dataset
2. Capture image, video, or webcam input
3. Detect vehicle number plate
4. Crop detected plate region
5. Extract plate text using OCR
6. Track vehicle movement direction
7. Classify status as IN or OUT
8. Save plate number, status, and timestamp into Excel

## Model Details

- Object Detection: Custom YOLOv8 Model
- Dataset: Number plate dataset from Roboflow
- Text Extraction: OCR Engine
- Data Storage: Excel file logging

## Applications

- Parking management systems
- College or office vehicle monitoring
- Gated community access control
- Automated security checkpoints
- Traffic management systems

## Future Improvements

- Improve OCR accuracy in low-light conditions
- Add database integration
- Implement automatic vehicle owner identification
- Deploy as a cloud-based application
- Add dashboard analytics for vehicle records

## Goal

The goal of this project is to combine deep learning, computer vision, and automation to create a practical system for real-world vehicle monitoring and entry management.

Built using Python, Computer Vision, and Machine Learning
