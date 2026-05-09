# Face Mask Detection

A deep learning-based **Face Mask Detection system** that can identify whether a person is wearing a mask or not in real-time using computer vision and CNN models.

---

## Overview

This project uses **OpenCV** and a **Convolutional Neural Network (CNN)** to detect faces and classify them into two categories:

* Mask
* No Mask

It works on both **static images** and **live webcam feeds**, making it useful for real-world safety monitoring applications.

---

## Features

* Real-time face detection using webcam
* Mask vs No Mask classification
* Lightweight and efficient model
* Easy to run and modify
* Supports image and video input

---

## Tech Stack

* Python
* OpenCV
* TensorFlow / Keras
* NumPy

---

## Project Structure

```
Face-Mask-Detection/
│
├── dataset/               # Dataset for training
├── model/                 # Saved trained model
├── detect_mask.py         # Script for real-time detection
├── train_model.py         # Script to train the model
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

---

## Installation & Setup

### Clone the repository

```bash
git clone https://github.com/sathvik-spartan/Face-Mask-Detection.git
cd Face-Mask-Detection
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## How It Works

1. Detect faces using OpenCV's pre-trained face detector
2. Preprocess detected face regions
3. Pass them into a trained CNN model
4. Classify output as **Mask** or **No Mask**
5. Display results with bounding boxes and labels

---

## Applications

* Public places monitoring
* Offices & workplaces
* Airports & railway stations
* Hospitals & healthcare

---

## Future Improvements

* Improve model accuracy with larger datasets
* Add face recognition with mask detection
* Deploy as a web or mobile app
* Use advanced models like YOLO or MobileNet

---

## Datasets
* There's a folder in this repo which contains a file through which the users can find various compatible repositories aligning with this project
* Add those into a file named "Data" or the users can rename their directory through which they can work on their custom data and suitable algorithms

## Contributions!   

> Contributions are welcome!
> Feel free to fork this repository and submit a pull request.

---
