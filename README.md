# Unity Cancer Cell Classification Project

This project integrates Unity with a Python-trained model to classify cancer cells as benign or malignant. The classification is done via a Flask server which processes the data and returns the result to Unity.

## Project Description
This project involves a Unity-based application where cancer cell assets are visualized. By clicking on these cells, data is sent to a Flask server which hosts a machine learning model trained to classify the cells as either benign or malignant.

## Features
- **Interactive Cancer Cells:** Clickable cancer cell assets in Unity.
- **Flask Server Integration:** Sends data from Unity to Flask server for processing.
- **Machine Learning Model:** Uses a trained Python model to classify cancer cells.
- **Real-time Feedback:** Displays classification result (benign/malignant) in Unity.

### Prerequisites
- Unity 2020.3 or later
- Python 3.8 or later
- Flask 2.0 or later
