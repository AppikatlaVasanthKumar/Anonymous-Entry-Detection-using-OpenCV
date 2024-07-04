# Anonymous Entry Detection System

## Introduction
The Anonymous Entry Detection System is designed to enhance security by detecting unauthorized entries into specified areas. 
This system utilizes Python, OpenCV, Twilio API, and IP Webcam technology to monitor and notify users of intrusions in real-time.

## Description
The Anonymous Entry Detection System captures live video feed from an IP Webcam using OpenCV for real-time image processing and analysis. 
It identifies unauthorized entries without performing facial recognition, focusing on motion and silhouette analysis. 
Upon detection, it triggers an alert via Twilio API to notify users through SMS. Users can also access the live video feed remotely for verification.

## Key Components

### Python:
  Backbone of the project for development and integration.
  
### OpenCV:
  Library for real-time computer vision tasks such as motion tracking and object recognition.
  
### Twilio API:
  Sends instant notifications to users via SMS.
  
### IP Webcam:
  Android app that turns a smartphone into a network camera for live video streaming.

## Functionality Overview

### Video Feed Acquisition: 
  Live video is streamed from the IP Webcam app to the Python application.
  
### Anonymous Entry Detection: 
  OpenCV analyzes the video feed for human presence.
  
### Notification Triggering: 
  System sends an SMS alert via Twilio API upon detecting an unauthorized entry.
  
### Remote Monitoring:
  Users can access the live video feed remotely through a web interface.

## Installation and Setup

### Install Required Libraries:
pip install opencv-python twilio

### Setup IP Webcam:
Install the IP Webcam app on your Android device.
Start the server and note the IP address.

### Configure Twilio API:
Create a Twilio account and obtain the necessary API keys.

### Run the Application:
Execute the Python script to start monitoring.
