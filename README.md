🧑‍🤝‍🧑 Facial Recognition System (OpenCV – Python)
📌 Project Overview

This project is a basic facial recognition system built using Python and OpenCV.
It detects human faces from images and identifies the most similar face from a given dataset using Haar Cascade face detection and histogram-based feature comparison.

⚠️ Note: This project is intended for educational and demonstration purposes only and is not production-ready facial recognition software.

🎯 Features

Upload dataset as a ZIP file (Kaggle compatible)

Automatic dataset extraction

Face detection using Haar Cascades

Feature extraction using grayscale histogram

Face comparison using histogram correlation

Confidence score for matched faces

Visual result display (uploaded image, detected face, matched face)

🛠️ Technologies Used

Python 3

OpenCV

NumPy

Matplotlib

Pillow (PIL)

🚀 How It Works
1️⃣ Dataset Upload

User uploads a dataset ZIP file (archive.zip)

ZIP file is extracted automatically

2️⃣ Face Detection

Uses Haar Cascade Classifier

Converts images to grayscale

Detects faces from images

3️⃣ Feature Extraction

Face region is resized to 100x100

Converted to grayscale

Histogram of pixel intensities is extracted

4️⃣ Face Comparison

Histogram correlation is calculated

Similarity score ranges from 0 to 1

Best match above threshold is selected

▶️ How to Run the Project
Step 1: Open in Google Colab

Upload the notebook to Google Colab

Step 2: Upload Dataset

When prompted:

Upload your dataset ZIP file

Ensure the ZIP contains folders named after individuals

Step 3: Upload Test Image

Upload a photo for recognition

The system will detect the face and compare it with dataset images

Step 4: View Result

Name of matched person

Confidence percentage

Visual comparison output
