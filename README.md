#  Covid-19 Violation Monitor 🦠📹
The system processes the surveillance videos to determine whether people in the video are wearing masks or not using the RetinaFace face detection model and Xception classification model.The system monitors if social distancing is maintained or breached in the video using the YOLOv3 object detector.

## Table of Contents

- [Features](#features)
- [Deployment](#deployment)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Constraints](#constraints)
- [Future Enhancements](#future-enhancements)

## Features

- *Face Mask Detection*: Uses models to efficiently detect individuals without masks.
- *Social Distance Monitoring*: Ensures distancing guidelines are maintained.
- *Face Recognition*: Accurately recognizes and catalogs individuals.
- *Reporting*: Detailed reports and lists of violations are downloadable in CSV format.

## Deployment

Hosted on Streamlit Sharing. [Visit the app](https://www.streamlit.io/).

## Setup & Installation
Detailed steps for developers or users to set up this project on their local machines. For instance:
bash
git clone https://github.com/yourusername/covid-violation-monitor.git
cd covid-violation-monitor
pip install -r requirements.txt


## Usage

Steps or code snippets demonstrating how to use the application. For instance:
bash
streamlit run app.py

Then, upload your video file to monitor for violations.

## Constraints

- Video clarity is crucial for optimal results.
- Upload limit of 200MB on Streamlit.
- Facial similarities might affect recognition accuracy.
- Beards may impact mask detection.
- Limited processing speed due to absence of GPU on the deployment platform.

## Future Enhancements

- Integration of FaceNet for better facial recognition.
- Image augmentation techniques for improved Face Recognition dataset creation.
- Adaptation for live CCTV or IP camera feeds for real-time monitoring.
