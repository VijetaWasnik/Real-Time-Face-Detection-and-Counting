# Real-Time Face Detection and Counting

This project demonstrates a simple real-time face detection and counting system using TensorFlow and OpenCV. The system captures video from the camera, detects faces, counts the number of people in front of the camera, and displays the count on the video feed.

## Features
- Real-time face detection using Haar Cascade Classifier.
- Count and display the number of people in front of the camera.
- User-friendly instructions displayed on the video feed.

## Requirements

- Python 3.x
- TensorFlow
- OpenCV

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/VijetaWasnik/face-detection-counting.git
    cd face-detection-counting
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the script:
    ```bash
    python face_detection.py
    ```

2. The camera will open, and the system will start detecting faces in real-time. The number of people detected will be displayed on the video feed.

3. Press `q` to quit the application.

## Project Structure

- `face_detection.py`: Main script to run the face detection and counting system.
- `requirements.txt`: List of Python packages required for the project.

## How It Works

The script uses OpenCV's Haar Cascade Classifier for face detection. The camera captures frames in real-time, and the classifier detects faces in each frame. The number of detected faces is counted and displayed on the video feed along with an instruction to press `q` to quit the application.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.
