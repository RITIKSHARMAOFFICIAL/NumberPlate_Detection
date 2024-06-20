# NumberPlate_Detection
![Gemini_Generated_Image_5kco5j5kco5j5kco](https://github.com/RITIKSHARMAOFFICIAL/NumberPlate_Detection/assets/96929769/7faa348b-39b5-449f-bbc4-d2549e90daf7)

## Automatic Number Plate Recognition Project

### Introduction

This project aims to develop an Automatic Number Plate Recognition (ANPR) system using TensorFlow and EasyOCR. The system captures real-time images via a webcam, detects vehicle license plates using TensorFlow Object Detection, and extracts the text from the plates using EasyOCR. This project is designed to ensure accurate plate detection and text extraction for various applications such as traffic management and security.

### Objective

The aim of this project is to develop an Automatic Number Plate Recognition (ANPR) system using TensorFlow and EasyOCR. This system will be capable of detecting vehicle license plates from images and extracting the text from the plates in real time.

### Workflow

1. **Image Acquisition**
   - Capture real-time images using a webcam feed or use pre-existing images.

2. **Object Detection using TensorFlow**
   - Utilize TensorFlow Object Detection to identify and isolate the region of interest (ROI), which in this case is the number plate.
   - The detection model will be trained on a [Kaggle dataset](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection) to accurately identify number plates in various conditions.
   - ![kaggle](https://github.com/RITIKSHARMAOFFICIAL/NumberPlate_Detection/assets/96929769/c6ea33d9-76ad-469c-9d8c-0946fda7f32b)


3. **Text Extraction using EasyOCR**
   - Employ EasyOCR to extract the alphanumeric characters from the detected number plate.
   - Implement a size filtering algorithm to focus on the largest detection region, ensuring the most accurate text extraction.
   - ![numberplatedetection1](https://github.com/RITIKSHARMAOFFICIAL/NumberPlate_Detection/assets/96929769/c1b11b2b-d026-468c-945f-31b69a5816af)


   


### Steps

1. **Setup**
   - Initial setup and configuration for the project, including installing necessary libraries and dependencies.

2. **Cloning Baseline Code**
   - Clone the baseline code repository to use as a starting point for the project.

3. **Creating a Virtual Environment**
   - Set up a virtual environment to manage project dependencies and ensure a consistent development environment.

4. **Installing Dependencies**
   - Install all required libraries and dependencies, including TensorFlow and EasyOCR.

5. **Installing TensorFlow Object Detection**
   - Install and configure TensorFlow Object Detection API.
   - Train the model on a Kaggle dataset to detect number plates.

6. **Implementing the Detection and OCR Pipeline**
   - Capture images from the webcam or load pre-existing images.
   - Apply the TensorFlow Object Detection model to locate the number plate in the image.
   - Use EasyOCR to extract the text from the detected number plate region.
   - Apply size filtering to improve the accuracy of the OCR process.
   - ![carimage2](https://github.com/RITIKSHARMAOFFICIAL/NumberPlate_Detection/assets/96929769/a547876a-d5b9-4dc9-b7f5-8d99f6a9ec80)
   - !![excelfile](https://github.com/RITIKSHARMAOFFICIAL/NumberPlate_Detection/assets/96929769/9f1deca4-9b1f-418a-913d-2ad666e3e59d)


### Conclusion

This project combines object detection and optical character recognition to create an efficient ANPR system. By following this workflow, you will develop a tool that can accurately detect and read vehicle license plates in real-time, which can be applied in various domains such as traffic management, security, and automated toll systems.

### Dataset

The dataset used for training the model can be downloaded from [Kaggle Car Plate Detection Dataset](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection).
