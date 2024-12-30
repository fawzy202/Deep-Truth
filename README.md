# **DeepFake Detection Project**

## **Overview**

DeepFake technology poses significant challenges in the realms of media integrity, identity protection, and cybersecurity. This project, DeepTruth, aims to develop robust machine learning models and tools to detect DeepFake content in both images and videos. By leveraging state-of-the-art AI architectures, we provide an effective solution for combating the spread of manipulated media.

## **Objectives**

**Model Development:** Build and train machine learning models to detect DeepFake-generated images and videos.

**Data Pipeline:** Develop a robust pipeline for collecting, preprocessing, and augmenting datasets of real and fake media.

**Web and Mobile Applications:** Deploy the detection models via user-friendly web and mobile platforms.

## **Models and Results**

## **Model 1: DeepFake Video Detection**

**Purpose:** Detect manipulated (face-swapped) videos.

**Datasets Used:**

  **FaceForensics++:** 1,613 samples (820 real, 793 fake).

  **DeepFake Detection Challenge (DFDC):** 3,272 samples (1,721 real, 1,551 fake).

  **Celeb-DF:** 1,171 samples (584 real, 587 fake).

**Architectures and Accuracy:**

**EfficientNet_B1:** 96.59%

**ResNet50:** 89.47%

**RegNet_Y_16GF:** 94.73%

**EfficientNet_B2:** 90.40%

## **Model 2: DeepFake Image Detection**

**Purpose:** Identify face-swapped fake images.

**Datasets Used:**

**Generated Dataset:** 6,570 samples (4,230 real, 2,340 fake).

**Data Collection Process:**

Collect real images from websites via APIs.

Extract facial landmarks (eyes, nose, mouth) using OpenCV.

Generate fake images using face-swapping APIs.

**Architectures and Accuracy:**

**MobileNet_v2:** 96.25%

**ResNext_50:** 91.31%

**MobileNet_v3:** 91.86%

## **Data Pipeline**

**Data Collection:**

Collect images and videos from reliable datasets.

Use APIs to automate the data generation process.

**Preprocessing:**

Detect faces and extract key landmarks using OpenCV.

Standardize image dimensions and normalize pixel values.

**Augmentation:**

Apply techniques such as flipping, rotation, and cropping to enhance dataset diversity.

## **Deployment**

## **DeepTruth Website**

A comprehensive platform for users to upload and analyze images or videos for authenticity.

**Features:**

Home: Overview of DeepFake detection.

Article Section: Educational content on DeepFakes.

Profile: User management and history.

**Technologies Used:**

Backend: Flask, Node.js

Database: MongoDB

## **DeepTruth Application**

A mobile application offering real-time detection capabilities.

## **Market Insights**

Market Growth Rate: 17.1%

Market Size: $1.2 billion (2022)

Yearly Growth: 31%

## **Getting Started**

## **Prerequisites**

Python 3.6 or higher

## **Required Libraries:**

pip install numpy

pip install opencv-python 

pip install tensorflow flask

## **Installation**

Clone the repository:

git clone https://github.com/fawzy202/DeepFake-Detection.git
cd DeepFake-Detection

## **Install dependencies:**

pip install tensorflow
pip install opencv-python
pip install numpy


## **Run the Models**

Prepare the datasets as per the Data Pipeline.

Train the model:

python train_model.py --model MobileNet_v3

python train_model.py --model MobileNet

python train_model.py --model resnet50

Evaluate on test data:

python evaluate.py --dataset test


## **Contributing**

We welcome contributions from the community! To contribute:

Fork the repository.

Create a new branch for your feature or bug fix.

Submit a pull request with detailed descriptions of your changes.


Contact

Email: fawzi.muhammad20@gmail.com

GitHub: fawzy202


