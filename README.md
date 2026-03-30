# Face-Detector
Readme · MD
Copy

# FaceDetector
 
Real-time face detection using Python and OpenCV with Haar Cascade classifiers, accessed via webcam.
 
## Demo
 
The program opens your webcam and draws a blue rectangle around every detected face in real time.
 
## Tech Stack
 
- Python
- OpenCV (`opencv-python`)
 
## Getting Started
 
### Prerequisites
 
- Python 3.x
- pip
 
### Installation
 
1. Clone the repo
   ```bash
   git clone https://github.com/Manas395/FaceDetector.git
   cd FaceDetector
   ```
 
2. Install dependencies
   ```bash
   pip install opencv-python
   ```
 
### Run
 
```bash
python Face_detector.py
```
 
Press **q** to quit the webcam window.
 
## How It Works
 
- Captures frames from the webcam in real time
- Converts each frame to grayscale
- Uses OpenCV's pre-trained Haar Cascade classifier (`haarcascade_frontalface_default.xml`) to detect faces
- Draws a blue bounding box around each detected face
 
## Project Structure
 
```
FaceDetector/
├── Face_detector.py
├── .gitignore
└── README.md
```
 
## Author
 
**Manas** — [GitHub](https://github.com/Manas395)