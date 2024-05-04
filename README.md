# VEHICLE-SPEED-TRACKING
# Overview
This repository contains the code for a vehicle detection and speed tracking system implemented using Python, OpenCV, and dlib libraries. The system is designed to accurately detect vehicles in real-time video streams, track their movements, and calculate their speeds based on pixel per meter (ppm) values.

# Key Features
Vehicle Detection: Utilizes a Haarcascade classifier for accurate vehicle identification.                               
Vehicle Tracking: Implements a corelation tracker from the dlib library to assign IDs and track vehicles.                     
Speed Calculation: Calculates vehicle speeds by measuring distance traveled in pixels per second and converting to meters per second using ppm values.                 
Manual PPM Estimation: Includes a method for manually estimating ppm values based on real-world road width and digital pixel measurements.                 
Python Virtual Environment: Utilizes virtual environments for project management and dependency isolation.             
Documentation: Includes detailed documentation on project setup, usage, and ppm estimation methodology.         
Getting Started

# To get started with the project, follow these steps:

Clone the repository:

git clone https://github.com/ekanshSE/VEHICLE-SPEED-TRACKING/tree/main

Navigate to the project directory:

cd VEHICLE-SPEED-TRACKING

Create a virtual environment:

python -m venv venv

Activate the virtual environment:

On Windows:
venv\Scripts\activate

On macOS/Linux:
source venv/bin/activate

Run the speed tracking script:
python speed_check.py

# Note
PPM values may vary for different roads and need to be adjusted accordingly.
Ensure accurate road width measurements for ppm estimation.

# Created By
https://github.com/ekanshSE
