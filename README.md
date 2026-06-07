# Edge-Vision: Edge AI Powered Elderly Fall Detection System

## Overview

Edge-Vision is an Edge AI based elderly healthcare monitoring system that detects falls in real-time using computer vision and pose estimation.

The system performs on-device AI inference using MediaPipe Pose and automatically triggers:

- Emergency dashboard alert
- ESP32 LED indication
- WhatsApp caregiver notification

## Features

✅ Real-time Fall Detection

✅ Edge AI Processing

✅ MediaPipe Pose Estimation

✅ ESP32 Hardware Integration

✅ WhatsApp Emergency Alerts

✅ Live Monitoring Dashboard

## Technology Stack

### Frontend
- HTML
- CSS
- JavaScript
- Tailwind CSS

### AI
- MediaPipe Pose

### Hardware
- ESP32 / ESP8266

### Communication
- WhatsApp API

## Architecture

Camera
↓
MediaPipe Pose
↓
Pose Landmarks
↓
Fall Detection Logic
↓
ESP32 + WhatsApp Alert

## Edge AI Implementation

The system uses MediaPipe Pose running directly on the user's device.

Since inference is performed locally instead of sending video streams to cloud servers, the solution qualifies as Edge AI.

Benefits:
- Low Latency
- Better Privacy
- Reduced Bandwidth Usage
- Offline Capability

## Future Enhancements

- Heart Rate Monitoring
- GPS Tracking
- Cloud Dashboard
- Mobile Application

## Author

Avanthika
