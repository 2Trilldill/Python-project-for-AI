# Emotion Detection Web App

This is a simple yet comprehensive Python web application that analyzes text for emotional tone using IBM Watson’s NLP API. Users can paste in any statement and receive scores across five emotions—anger, disgust, fear, joy, sadness—along with the dominant emotion.

## Features

- **Emotion Analysis**: Powered by IBM Watson EmotionPredict API.
- **Web Interface**: Built with Flask and Bootstrap for easy input and results display.
- **Robust Error Handling**: Gracefully handles empty strings and API failures.
- **Unit Tested**: Five-unit test suite ensures accuracy for joy, anger, disgust, fear, and sadness.
- **Production-Ready Quality**:
  - Packaged as a reusable Python module.
  - Code quality ensures 10/10 Pylint score.

## How to Run

1. **Clone and Install**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/oaqjp-final-project-emb-ai.git
   cd oaqjp-final-project-emb-ai
   pip install -e .
   pip install --user flask pylint requests
