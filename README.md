# No of Faces Detection App

This is a Flask application for detecting the number of persons (faces) in a photo using the YOLO model. The application allows users to upload an image, and it returns the number of faces detected in the image.

## Features

- Detect faces in an uploaded image.
- Return the count of faces detected.
- CORS enabled for cross-origin requests.

## Requirements

- Python 3.6+
- Flask
- Flask-CORS
- OpenCV
- ultralytics (YOLO)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/face-detection-app.git
   cd face-detection-app
2. Install the required packages:
   ```sh
   pip install -r requirements.txt
3. Run the Flask app
   ```sh
    python app.py
4. The app will be available at `http://localhost:5000`    
