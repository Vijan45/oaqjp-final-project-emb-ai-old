# Emotion Detector

Final project for the IBM course *Developing AI Applications with Python and Flask*.

A web app that detects emotions (anger, disgust, fear, joy and sadness) in a piece of text using the Watson NLP Emotion Predict service, and reports the dominant one.

## Project structure

```
EmotionDetection/
    __init__.py
    emotion_detection.py
static/
    mywebscript.js
templates/
    index.html
server.py
test_emotion_detection.py
```

## Running

```
python3.11 -m pip install flask requests
python3.11 server.py
```

Then open http://localhost:5000 in the browser.

## Tests

```
python3.11 test_emotion_detection.py
```
