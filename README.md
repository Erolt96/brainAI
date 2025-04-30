# BrainAI – Image Classification with ImageAI & MobileNetV2

BrainAI is an AI-powered image recognition tool built using Python and the ImageAI library. It uses the MobileNetV2 model to analyze uploaded images and return the top 5 object predictions with confidence scores.

## Features
- Pre-trained MobileNetV2 model
- Predicts contents of any uploaded image (e.g. Godzilla, house)
- Fast, simple, and lightweight
- CLI-based with customizable output

## Tools Used
- Python
- ImageAI
- TensorFlow / Keras
- MobileNetV2

## How to Use
1. Install dependencies: `pip install imageai tensorflow`
2. Place your image (e.g. `godzilla.jpg`) in the working directory
3. Run the script:
   ```python
   python brainai.py
