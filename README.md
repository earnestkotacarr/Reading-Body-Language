# Real-Time Pose Estimation and Sentiment Analysis

This project demonstrates an intelligent machine capable of real-time pose estimation and sentiment analysis using video input. Utilizing TensorFlow.js and PoseNet, the system analyzes body language to calculate lean scores derived from video captured via webcam. These scores are used to infer sentiment and interaction dynamics between individuals.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The project showcases real-time pose estimation and sentiment analysis from video input, providing insights into interpersonal dynamics. By detecting body landmarks and calculating lean scores, the system can analyze body language and infer sentiment between participants.

## Features

- **Real-Time Pose Estimation:** Analyzes video input from a webcam to detect body landmarks using PoseNet.
- **Lean Score Calculation:** Calculates lean scores based on the detected body landmarks to infer body language.
- **Event Detection:** Identifies significant events based on changes in lean scores.
- **Data Visualization:** Displays the video input, annotated poses, lean scores, and significant events dynamically.

## Usage

1. **Clone the Repository:**
   ```sh
   https://github.com/earnestkotacarr/Reading-Body-Language.git

 2. Navigate to the Project Directory:

cd Reading-Body-Language


 3. Open the index.html File in Your Browser:
 • Simply open the index.html file in your preferred web browser to start the demo.
 • The system will request access to your webcam to capture real-time video input.

Future Enhancements

 • Unsupervised Learning for Sentiment Analysis:
 • Integrate advanced unsupervised learning techniques such as K-Means clustering or DBSCAN for more sophisticated event detection and sentiment analysis.
 • Training on Diverse Video Inputs:
 • Develop a training process using diverse video inputs, including interview videos, to enhance the system’s ability to analyze different forms of body language and interpersonal dynamics.
 • Support for Uploaded Video Files:
 • Extend the system to support analyzing uploaded video files, allowing for retrospective sentiment analysis and broader application scopes.
 • Application Development:
 • Adapt the system for specific applications such as interview analysis, virtual meetings, and social interaction studies, where understanding participant sentiment and engagement is crucial.

Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or create a pull request. For major changes, please discuss them in an issue first to ensure alignment with the project goals.