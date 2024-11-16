# Real - Time Gerbera Flowers Counting and Classification System using YOLO and UAV based approach

## Project Overview
This project implements a **hardware + software-based system** for counting and categorizing Gerbera flowers in real-time. Using UAV (Unmanned Aerial Vehicle) technology for image capture and YOLO for object detection, the system classifies flowers by color and provides accurate counts directly on the ground system.

## Key Features
- **Real-Time Processing**: UAV captures images and transmits them to a ground system where the trained YOLO model performs real-time flower detection and classification.
- **High Accuracy**: 
  - **87%** for images
  - **83%** for videos
  - **84%** for real-time data
- **Comprehensive Dataset**: Created a custom dataset of over **600+ images** and **90+ videos** of Gerbera flowers.
- **Interactive UI**: Designed using Streamlit for ease of use and visualization.

## Responsibilities
- **Dataset Preparation and Preprocessing**: Organized and labeled data using Roboflow.
- **Model Building**: Trained YOLO V8 for high accuracy in detection and classification.
- **Documentation**: Prepared detailed reports and project documentation.
- **Research Publication**: Published findings in a research paper.

## Technologies Used
- **Model and UI**: Python, YOLO V8, Streamlit
- **Dataset Preparation**: Roboflow
- **Data Collection**: Quadcopter Drone

## How It Works
1. **Data Collection**: A UAV captures images and videos of Gerbera flower farms.
2. **Data Transfer**: Captured media is transmitted to the ground system via a transmitter.
3. **Real-Time Processing**:
   - The YOLO model detects Gerbera flowers in the images/videos.
   - Flowers are counted and categorized based on their color.
4. **User Interaction**: Results are displayed on a user-friendly Streamlit interface.

## Results
- **Image Classification Accuracy**: 87%
- **Video Classification Accuracy**: 83%
- **Real-Time Detection Accuracy**: 84%

## Links
- **Project Application**: [Object Detection - Roboflow Train](https://detectt.streamlit.app/Object_Detection_-_Roboflow_Train)
- **Demo Video**: [Watch Demo](https://drive.google.com/file/d/10_r8WeCkhuQGYsUWLiXSg9h2CJZgIn7P/view?usp=drive_link)
- **Gerbera Dataset Link (Kaggle)**: [Gerbera Dataset](https://www.kaggle.com/datasets/rujulmodi/gerbera-flower-dataset)

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone <repository-link>
   cd <repository-directory>
## Installation Dependencies
- pip install -r requirements.txt

## To run the application
- streamlit run app.py
