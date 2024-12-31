# **DeepFake Detection Project**

## **Table of Contents**

1. [Overview](#overview)
2. [Objectives](#objectives)
3. [Models and Results](#models-and-results)
   - [Model 1: DeepFake Video Detection](#model-1-deepfake-video-detection)
   - [Model 2: DeepFake Image Detection](#model-2-deepfake-image-detection)
4. [Data Pipeline](#data-pipeline)
5. [Deployment](#deployment)
   - [DeepTruth Website](#deeptruth-website)
   - [DeepTruth Application](#deeptruth-application)
6. [Market Insights](#market-insights)
7. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Required Libraries](#required-libraries)
   - [Installation](#installation)
   - [Run the Models](#run-the-models)
8. [Contributing](#contributing)
9. [Contact](#contact)
## **Overview**

DeepFake technology poses significant challenges in the realms of media integrity, identity protection, and cybersecurity. This project, DeepTruth, aims to develop robust machine learning models and tools to detect DeepFake content in both images and videos. By leveraging state-of-the-art AI architectures, we provide an effective solution for combating the spread of manipulated media.

**short video about the danger of deep fake technology**


https://github.com/user-attachments/assets/d177a5ee-dc15-4fd4-adc9-b06ae0a511ef

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

## Result

![fake](https://github.com/user-attachments/assets/aea6feb3-7d59-42c9-8a80-4b630ccf94fb)

![real](https://github.com/user-attachments/assets/7b4adbed-bde6-4c37-80f8-ce455dfeb625)

![WhatsApp Image 2024-12-25 at 12 55 01_99aff856](https://github.com/user-attachments/assets/7fd3f488-87f6-402d-8c7d-30a340036f21)

![WhatsApp Image 2024-12-25 at 12 55 01_9f41a095](https://github.com/user-attachments/assets/95a6aa81-096e-4656-bbed-011b23bbb418)

![Screenshot 2024-12-31 114130](https://github.com/user-attachments/assets/cb79dcc1-3fb0-402e-8867-36708a43c4f4)

![WhatsApp Image 2024-12-25 at 12 55 02_ce97c143](https://github.com/user-attachments/assets/55ec225e-f94b-489e-a7f0-2e1fc164973f)

![Screenshot 2024-12-31 114247](https://github.com/user-attachments/assets/ef15f735-b4f1-4aca-ac8b-bcd65cbff479)




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

![Uploading WhatsApp Image 2024-12-31 at 01.05.27_72264716.jpg…]()


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


