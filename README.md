# Car License Plate Detection and ANPR with YOLOv7

This project implements a car license plate detection system using YOLOv7 (You Only Look Once) for object detection and ANPR (Automatic Number Plate Recognition) for recognizing and extracting text from license plates. The project is built with a Flask backend, providing a REST API, and uses Swagger for API documentation.

## Features

- **License Plate Detection**: YOLOv7 detects and localizes license plates from images or video streams.
- **Automatic Number Plate Recognition (ANPR)**: OCR (Optical Character Recognition) is used to extract the license number from detected plates.
- **REST API**: The project uses Flask to provide a REST API for integrating with other services or frontend applications.
- **Swagger Documentation**: Automatically generated API documentation with Swagger.
- **Real-time Processing**: Capable of real-time license plate detection from live video feeds or pre-recorded content.

## Technologies

- **YOLOv7**: Deep learning model for detecting license plates.
- **OCR (Tesseract or PaddleOCR)**: Used for extracting text from detected license plates.
- **Flask**: Backend framework providing the REST API.
- **Swagger**: API documentation and testing interface.
- **OpenCV**: Library for handling video streams and image processing.
- **Python**: Primary language for backend and model integration.
