# Repository for final project
# Emotion Detection Application

This project implements an emotion detection web application for the IBM final project assignment.

The application sends user text to the Watson NLP emotion prediction endpoint, formats the five emotion scores, identifies the dominant emotion, and exposes the result through a Flask web interface.

# Final project

This project is an AI-based Emotion Detection web application developed using the Watson NLP library and Flask.

## Features
- Emotion detection using Watson NLP
- Detection of anger, disgust, fear, joy, and sadness
- Identification of dominant emotion
- Flask web deployment
- Error handling for invalid input
- Unit testing and static code analysis

## Author
Moumita Das

## Repository

Forked repository:

https://github.com/Mou4338/final_project

## Project Structure

```text
final_project/
|-- EmotionDetection/
|   |-- __init__.py
|   `-- emotion_detection.py
|-- static/
|   `-- mywebscript.js
|-- templates/
|   `-- index.html
|-- README.md
|-- requirements.txt
|-- server.py
`-- test_emotion_detection.py
```

## Run Locally

Install dependencies:

```bash
pip install -r requirements.txt
```

Run unit tests:

```bash
python -m unittest test_emotion_detection.py
```

Run the Flask application:

```bash
python server.py
```

Then open:

```text
http://localhost:5000
```

Run static code analysis:

```bash
pylint server.py
```
