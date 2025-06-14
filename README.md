# AI-Based Emotion Detection Web Application 

This project is part of the final assignment for the "Working with AI Applications" course. It uses IBM Watson NLP to detect emotions in customer feedback and deploys the system as a Flask web application.

## Overview

The application takes customer feedback text as input and uses IBM Watson's `EmotionPredict` service to identify and return the levels of:
- Anger 😠
- Disgust 🤢
- Fear 😨
- Joy 😄
- Sadness 😢

The output also includes the **dominant emotion** based on the highest score.
![image](https://github.com/user-attachments/assets/8763e947-b888-4f91-b7a6-e2f413927fa7)


## Tech Stack

- **Python 3.8+**
- **Flask** – Web framework
- **Requests** – To send HTTP requests to Watson API
- **IBM Watson NLP** – Cloud-based Emotion Prediction
