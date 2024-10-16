
# Face Emotion Detection System

This emotion detection system utilizes a combination of computer vision and deep learning to identify human emotions from video feeds. By leveraging a pre-trained face detection model and a custom emotion classifier, it analyzes facial expressions in real time. The system captures video from a camera, processes the frames, and displays both the detected emotions and their probabilities through dynamic histograms. This tool has potential applications in fields such as mental health, user experience, and interactive media.


## Run Locally

Clone the project

```bash
  git clone https://github.com/chamoddissanayake/Face-Emotion-Detection-System.git
```

Install dependencies

```bash
  pip install -r requirements.txt
```

If your device has multiple cameras, change camera id accordingly in this line
```bash
  camera = cv2.VideoCapture(0)
```

Start the Application

```bash
  python face.py
```


## Tech Stack

**Programming Language:**

* Python

**Libraries and Frameworks:**

* OpenCV: For image processing and video capture.
* Keras: For building and loading deep learning models.
* NumPy: For numerical operations and array handling.
* Imutils: For easier image processing functions.
* Matplotlib: For plotting histograms and visualizing data.
* Playsound: For audio playback

**Model Files:**

* Haar Cascade Classifier: For face detection.
* Pre-trained Emotion Recognition Model: e.g., Mini XCEPTION model.

**Dependencies:**

* OpenCV, Keras, NumPy, Imutils, Matplotlib, Playsound