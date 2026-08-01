# Face Detection using OpenCV

A simple Python application that performs real-time face detection using your computer's webcam. It uses OpenCV's Haar Cascade classifier to detect human faces and draws bounding boxes around them.

## Features

- Real-time face detection using webcam
- Detects multiple faces simultaneously
- Draws rectangles around detected faces
- Lightweight and easy to use
- Exit the application by pressing the **ESC** key

## Technologies Used

- Python 3
- OpenCV (cv2)
- Haar Cascade Classifier

## Project Structure

```
face-detection/
│
├── main.py
├── requirements.txt
└── README.md
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/face-detection.git
cd face-detection
```

### 2. Create a virtual environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

## Usage

Run the application:

```bash
python main.py
```

The application will:

1. Open your default webcam.
2. Detect faces in real time.
3. Draw blue rectangles around detected faces.
4. Close when you press the **ESC** key.

## How It Works

- Captures video frames from the webcam.
- Converts each frame to grayscale.
- Uses OpenCV's pre-trained Haar Cascade classifier to detect faces.
- Displays the processed video with bounding boxes around detected faces.

## Requirements

- Python 3.8+
- Webcam
- OpenCV

## Future Improvements

- Eye detection
- Smile detection
- Face recognition
- Save detected face images
- Support for video file input

## License

This project is licensed under the MIT License.
