# Face Attendance Recognition System

A **Face Attendance Recognition System** built with **Python**, **OpenCV**, and **K-Nearest Neighbors (KNN)** using **scikit-learn**. This system is designed to automate attendance marking by recognizing faces and recording attendance timestamps, making it suitable for educational institutions or office environments.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [License](#license)

## Features

- **Face Detection**: Detects faces in real-time from a webcam feed or from static images using OpenCV.
- **Face Recognition**: Uses a K-Nearest Neighbors (KNN) classifier for recognizing faces and identifying individuals.
- **Automatic Attendance**: Marks attendance automatically by recognizing faces and recording the detection time.
- **CSV Integration**: Stores attendance data (names and timestamps) in a CSV file for easy management.

## Requirements

- **Python 3.x**
- **OpenCV**
- **scikit-learn**
- **numpy**
- **pandas**
- **pywin32** (optional, for Windows COM support)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/chathuranga155/face-attendance-recognition-system.git
   cd face-attendance-recognition-system


## project structure

face-attendance-recognition-system/
│
├── data/                            # Directory for storing data files
│   ├── faces_data.pkl               # File to store face encodings (generated after training)
│   ├── names.pkl                    # File to store names associated with face encodings
│   └── haarcascade_frontalface_default.xml  # XML file for face detection using OpenCV
│
├── train/                           # Directory for training images (organized by person)
│   ├── person1/                     # Folder with images of Person 1
│   ├── person2/                     # Folder with images of Person 2
│   └── ...                          # Additional folders for each person
│
├── Attendance.py                    # Main script for running the attendance recognition system
├── Dataset.py                       # Script for managing the face dataset (adding, updating faces)
├── attendance.csv                   # Output CSV file for attendance records
├── requirements.txt                 # Required dependencies
├── .gitignore                       # Git ignore file to exclude unnecessary files
└── .idea/                           # IDE configuration files (optional, used by PyCharm or similar)
    ├── inspectionProfiles/          # Inspection profiles for code quality checks
    ├── profiles_settings.xml        # IDE-specific settings
    ├── Project_Default.xml          # Default project settings
    


